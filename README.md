# ChatDoc
chat with pdf and other docuemnts which can be extracted to text

# run the webui
1. prepare the virtual env
```shell 
conda create -n smartdoc_env python==3.9.16  
conda activate smartdoc_env  
pip install -r requirements.txt    
```


2. run the webui server

```shell  
cd src  
```

```python  
python webui.py  
```

[//]: # (![chatdoc-webui]&#40;images/chatdoc-webui.jpg&#41;)

3. upload the pdf and process the pdf

[//]: # (![upload-pdf]&#40;images/chatdoc-upload-pdf.jpg&#41;)

4. ask the question and get the answer  

[//]: # (![chat-in-webui]&#40;images/chatdoc-chat.jpg&#41;)


# server configs
src/configs/config.py
