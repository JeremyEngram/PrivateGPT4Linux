## Requirements
. Python-pip

## How to install

```
sudo apt install python-pip
git clone https://github.com/JeremyEngram/PrivateGPT4Linux.git; cd PrivateGPT4Linux; sudo chmod +x installer.sh
sudo ./installer.sh
```

## How to use

### 1. Ingest documents
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
cd /home/$USER/privateGPT && python3 ingest.py
```
### 2. Run privateGPT
```
cd /home/$USER/privateGPT && python3 privateGPT.py
```
