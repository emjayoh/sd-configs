For Kaggle
Copy and edit https://www.kaggle.com/code/camenduru/stable-diffusion-webui-kaggle (to get the old environment required) then use File>Import the fast release.ipynb

For Colab

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

