sudo apt update && sudo apt upgrade -y

sudo apt install git python3 python3-pip python3-venv -y

git clone https://github.com/amarb7047/hyp.git

cd hyp/

unzip hyperbolic.zip 

cd chatbot-app/

python3 -m venv venv
source venv/bin/activate
pip install requests


nano chat.py

python3 chat.py
