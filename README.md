# Humanoid_project
Dosthi is a chatbot that can answer the queries of a freshman joining IIT Bombay.
It was developed with Rasa open source software.
The installation steps for rasa are listed below:
* Rasa is built on python, so install the latest version of python from the official website
* Make sure pip3 is installed using 'pip3 --version',else install it
* Create a new virtual environment by choosing a Python interpreter and making a ./venv directory to hold it using 'python3 -m venv ./venv'
* Activate the virtual environment using 'source ./venv/bin/activate'
* Install rasa using 'pip3 install rasa'
  Once rasa is installed go inside the 'Dosthi' directory
  Train the model using 'rasa train' and to start chatting with the bot use 'rasa shell -m models'
  Queries Dosthi can respond to :
  1)Respond to greeting messages
  2)Identify which are girls hostel and which are boys hostel
  eg: 'Is H10 a girls hostel' to which Dosthi replies 'Yes, H10,H11 and H15 are girls hostels'
  3)Timings of the central library and the reading hall
  4)The course list for the first semester
