## Requirements
. NVIDIA GPU

. Linux

## How to install privateGPT

```
cd /path/to/file

sh installer.sh

python3 /home/$USER/privateGPT/privateGPT.py
```

## Ingest documents
. Put any and all your files into the `source_documents` directory.
The supported extensions are:

   - `.csv`: CSV,
   - `.docx`: Word Document,
   - `.doc`: Word Document,
   - `.enex`: EverNote,
   - `.eml`: Email,
   - `.epub`: EPub,
   - `.html`: HTML File,
   - `.md`: Markdown,
   - `.msg`: Outlook Message,
   - `.odt`: Open Document Text,
   - `.pdf`: Portable Document Format (PDF),
   - `.pptx` : PowerPoint Document,
   - `.ppt` : PowerPoint Document,
   - `.txt`: Text file (UTF-8),

Run the following command below to ingest the data.
```
cd /home/$USER/privateGPT && sudo python3 /home/$USER/privateGPT ingest.py
```
## Run privateGPT
```
cd /home/$USER/privateGPT && sudo python3 privateGPT.py
```
## Documentation
https://github.com/imartinez/privateGPT
