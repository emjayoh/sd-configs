Old Readme

# For Kaggle
### New Python 3.10.10 Notebook

|  Link | Python Version | Readme Page
| --- | --- | --- | 
[![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/roykent/stablediffusionwebui-configured) | 3.7.12 | [Readme](https://github.com/ark5mith/stable-diffusion-webui-colab/blob/community/ark5mith/readme.md)
[![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/roykent/automatic1111-s-stable-diffusion-webui-configured) | 3.10.10 | [Readme](https://github.com/ark5mith/stable-diffusion-webui-colab/blob/community/ark5mith/readme.md)

<img width="239" alt="image" src="https://user-images.githubusercontent.com/115693126/236795810-5f5595a8-e683-4653-9118-a47b0a713194.png">

Use github branch to have separate config
My default Python 3.7.12 on Camenduru v2.0 notebook use the branch `v2.0` which also the `main`

For the latest WebUI in kaggle with Python 3.10.10 copied from [RogueWild]() i use `rw10` branch
Using variable for ease of use. Switching by just typing which version.
<img width="469" alt="image" src="https://user-images.githubusercontent.com/115693126/236796150-ebad641a-a9e5-4fef-945e-c724129482b2.png">
<img width="469" alt="image" src="https://user-images.githubusercontent.com/115693126/236796384-8e28e747-2995-4cba-8994-911f72ca3ce1.png">

```Python
webui_settings = "https://github.com/ark5mith/sd-configs"
webui_settings_branch = "rw10" #other branch from my repo is "main" or "v2.0"

def use_config():
    %cd $install_path/stable-diffusion-webui
    if not os.path.exists(f"{install_path}/stable-diffusion-webui/tmp"):
    # do something
        !mkdir -p tmp
    %cd tmp
    if not os.path.exists(f"{install_path}/stable-diffusion-webui/sd-configs"):
        !git clone -b $webui_settings_branch $webui_settings sd-configs
        !cp -rf sd-configs/dist/* $install_path/stable-diffusion-webui

```





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

