Code for YouTube Tutorial 

[Tutorial Link](https://www.youtube.com/watch?v=WYzFzZg4YZI)

## Installation

- Clone the repository:
- cd into your directory/ open with vscode
- Create a Virtual Environment:
- `python -m venv env`
- Run the virtual environment: env/Scripts/activate - for Linux, env/Scripts/activate.bat - for Windows cmd, env/Scripts/Activate.ps1 - for Windows PowerShell 
- Install the required dependencies:
- `pip install -r requirements.txt`
- Create OpenAI API Key and add it to your .env file (don't forget to remove "copy" extension from the .env before run)
- Run the application:
- `streamlit run app.py`

In case you're facing "PermissionError: [WinError 10013] An attempt was made to access a socket in a way forbidden by its access permissions" on Windows try to run following commands in elevated PowerShell 
`net stop hns`
`net start hns`


## Please subscribe to the channel and give a follow on GitHub ⭐️
