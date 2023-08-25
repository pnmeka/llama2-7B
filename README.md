# llama2-7B
downloading and running llama2-7B chat on linux debian

Here are the steps I took to download and run my llama2 7B chat model:
1. Go to https://ai.meta.com/resources/models-and-libraries/llama-downloads/ to request a license to download. You should soon get an email with the download link.
2. Go to your desired folder and git clone the repo:

       git clone https://github.com/facebookresearch/llama
3. Go to the cloned repo

       cd llama
4. Runt the download.sh file from terminal

       bash ./download.sh
5. It should prompt you to paste link. Now paste the link in your email here that begins with https://download.llamameta.net.....
6. It should then prompt you to choose the model. I entered 7b-chat

       Enter the list of models to download without spaces (7B,13B,70B,7B-chat,13B-chat,70B-chat), or press Enter for all: 7B-chat

 7. The process should now begin. It took me almost 10 minutes to download the model.      
