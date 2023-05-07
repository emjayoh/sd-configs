Old Readme

# For Kaggle
### New Python 3.10.10 Notebook
testing branch for the latest notebook, use `!git clone -b 3.10` for example for cloning branch

|  Link | Python Version | Readme Page
| --- | --- | --- | 
[![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/roykent/stablediffusionwebui-configured) | 3.7.12 | [Readme](https://github.com/ark5mith/stable-diffusion-webui-colab/blob/community/ark5mith/readme.md)
[![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/roykent/automatic1111-s-stable-diffusion-webui-configured) | 3.10.10 | [Readme](https://github.com/ark5mith/stable-diffusion-webui-colab/blob/community/ark5mith/readme.md)


# For Colab
---
|  Link | Function or Name | Readme Page
| --- | --- | --- | 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ark5mith/stable-diffusion-webui-colab/blob/community/ark5mith/INSTALL_UPDATE_ConfigDrive_Colab_Kaggle.ipynb) | First-time run-first. Or updating extensions.| [Readme](https://github.com/ark5mith/stable-diffusion-webui-colab/blob/community/ark5mith/readme.md)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ark5mith/stable-diffusion-webui-colab/blob/community/ark5mith/RUN_ConfigDrive_Colab_Kaggle.ipynb) | For running WebUI | [Readme](https://github.com/ark5mith/stable-diffusion-webui-colab/blob/community/ark5mith/readme.md)

Old Link
Install and Update Notebook:  https://colab.research.google.com/drive/1mPw7WjKz16LTOpKCxFdLs_H5_CmPPiaJ?usp=sharing

Run Notebook:
https://colab.research.google.com/drive/1NqOmb_fq5DcLI9HkzG5zB77xyKI8zfJn?usp=sharing

run Notebook with ngrok https://colab.research.google.com/drive/1HGSyMkIi2aQzDgJe_68EelpV0W3wmuo_?usp=sharing

register in ngrok.com, then copy your Authtoken https://dashboard.ngrok.com/get-started/your-authtoken

to ngrokToken='yourtoken'
for example ngrokToken='akwofao8y9yw9fyoaw9naof_7oya78eyfbaey'

for secrecy you can use ngrokTokenFile='yourfilepath/filename.txt'
example ngrokTokenFile='/content/drive/Shareddrives/COLAB/configs/ngrok_token.txt'
inside the text file, you just need to put one line yourtoken like akwofao8y9yw9fyoaw9naof_7oya78eyfbaey

The ngrok process errored on start: The authtoken you specified does not look like a proper ngrok tunnel authtoken
this mean you haven't changed the ngrokToken or the token is invalid (not copied fromhttps://dashboard.ngrok.com/get-started/your-authtoken)

leave it empty  ngrokToken='' like that if not used 

