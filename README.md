# Python Virtual Assistant Base
A base model for the Python Virtual Assistant

# Setup instructions
- Copy the directory you have cloned from GitHub into whereever you want.

- Inside that directory, create a directory called 'venv' and initialize a python virtual environment in there.

- Now open a terminal and activate that virtual environment.

- Now cd to the root directory of the project (the directory that contains 'Assistant' & 'venv' & 
'setup.py').

- Run the following command: > *pip install -e .*
(This will install the Assistant package)

- Now you need to install the following pip packages: **pyttsx3**, **SpeechRecognition** and **PyAudio**
(If you are on Windows, you cannot install PyAudio normally, you have to install the actual .whl file that is provided, simply run: > *pip install .\PyAudio-0.2.11-cp38-cp38-win_amd64.whl)*

- Now to start the assistant either manually start the assistant.py file or run either start.bat or start.sh

# Development
The project is structured as a python package, all the skills that you develop for the assistant should go into the Skills directory. You can then import those skills from anywhere in the project like so:
```
import Assistant.Skills.YOUR_SKILL
```

If you develop a skill and you want to put it up on the organization page, make sure to clearly indicate what pip packages need to be installed and any instructions on how to use your skill in the README.md file.
Then email me at: **timofey.work@protonmail.com** and ask me to review the skill you made, I will then create a repo for it on the organization page

