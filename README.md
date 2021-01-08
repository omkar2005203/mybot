# mybot
Integrate Rasa chatbot on webpage and run on  local host
steps and requirements for Rasa installation in virtual envoirnment.

(base) PS C:\Users> cd D:\projects\mybot

(base) PS D:\projects\mybot> Conda create --name chatbotvenv python==3.7.6

To  activate this environment, use
#Jm
#     $ conda activate chatbotvenv
#
# To deactivate an active environment, use
#
#     $ conda deactivate

conda install ujson==2.0.3

conda install tensorflow==2.1.0

pip install rasa==1.10.0





///////////////////////////////////////////////////


to see list of envoirnment

conda env list

conda activate  <env name>

///////////////////////////////////////////////////////

rasa commands

// initialize files
rasa init

// train model
rasa train

// start shell

rasa shell

/////////////

// to run bot on page

rasa run --cors "*" --debug

// run index.html
