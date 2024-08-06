

#generate ssh key
ssh-keygen -t rsa

#get ssh key from codespace 
cat ~/.ssh/id_rsa.pub

#add the key to github ssh key as a new key

#git clone
git clone git@github.com:cheranratnam87/NLP_Text_Blob.git

#venv

python -m venv ~/.venv

#bash config

vim ~/.bashrc

#add this in bash

source ~/.venv/bin/activate

#to test the FAST API

#run

python main.py

open the server and modify url with wikiphrases/Los_angeles_lakers 
#enter whichever phrase name

#try out the docs feature --

https://friendly-goldfish-pw479946jq72rgxw-8080.app.github.dev/docs