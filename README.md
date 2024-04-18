# Multilingual-AI-Assistant

## How to run?

STEPS:
Clone the repository


Project repo: https://github.com/aariz120/Multilingual-AI-Assistant.git


## STEP 01- Create a conda environment after opening the repository

conda create -n llmapp2 python=3.8 -y


conda activate llmapp2


## STEP 02- install the requirements


pip install -r requirements.txt


## Create a .env file in the root directory and add your GOOGLE_API_KEY credentials as follows:

GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"


# Finally run the following command
  streamlit run app.py

NOW,

open up localhost:


## Techstack Used:

    Python
    Google API
    Streamlit
    PaLM2
    s2t
    t2s


1. How to Deploy Streamlit app on EC2 instance


2.Login with your AWS console and launch an EC2 instance

## Note: Do the port mapping to this port:- 8501

  sudo apt update

  sudo apt-get update

  sudo apt upgrade -y

  sudo apt install git curl unzip tar make sudo vim wget -y

  git clone "Your-repository"


  sudo apt install python3-pip

  # Important command:
  ''''
  sudo apt install portaudio19-dev
  python3 -m  pip install PyAudio
  ''''

  pip3 install -r requirements.txt

  #Temporary running
python3 -m streamlit run app.py


#Permanent running
nohup python3 -m streamlit run app.py


Note: Streamlit runs on this port: 8501


