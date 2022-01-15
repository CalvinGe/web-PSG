# web-PSG
Download the web-PSG-git.zip file and unzip it. Run the project with Django environment.

# Brief Instruction:
* Make sure all required dependencies are installed in your Django environment.
* The project needs to connect to your local database. Change the connection in **/webPSG/settings.py**
* You may ignore the predict.zip since it is an extra application for our neural network.
* The data is in **web-PSG-git.zip / Mypsg.sql**, run it in mysql to import the structure of our database along with the data.
* edf_data exceeds the limit of file size, and it is only used for our neural network. They can be accessed by visit: https://physionet.org/
