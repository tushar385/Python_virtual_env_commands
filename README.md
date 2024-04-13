## Install Python 

sudo apt update

sudo apt install python3

sudo apt install python3-pip


## Create Virtual env
python3 -m venv api_venv

## Activate Virtual_env
source api_venv/bin/activate

## Deactivate Virtual_env 
deactivate

## Delete Virtual_env
rm -rf api_venv

## List of Installed libraries in Env
pip list
