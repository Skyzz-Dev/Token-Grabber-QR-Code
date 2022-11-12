# Token-Grabber-QR-Code

Disclaimer
Bot was made for Educational purposes
This project was created only for good purposes and personal use.
By using this Bot, you agree that you hold responsibility and accountability of any consequences caused by your actions.
Features
Async QR Code Management
Using Websockets (no browser used)
Personal QR Code (visible only to the person passing the verification)
Saves the information in a json file
Gives a role to the user after his verification
Easy to use + Intuitive UI
How To Setup/Install
First of all please set your informations in the config.json file!
{
    "botToken": "TOKEN-HERE", #For more information, read below
    "prefix": "PREFIX-HERE",
    "command_name": "COMMAND-NAME-HERE",
    
    "give_role": false, #Can take the value: true or false
    "role_name": "ROLE-NAME-HERE" #Name of the role you want to give to the user after scanning the QR Code
}
Set up and invite your Bot.
Create a bot on the Discord Developer page
Enable all instances in the "Bot" tab
Invite your bot using this invite (replace CLIENTID by the ID of your Bot)
1st・Installation (Automated installation)
Launch the setup.bat file. A new file will be created. You will only have to launch it.
2nd・Installation (Manual installation)
$ git clone https://github.com/SenT/Fake-Verification-Bot.git
$ python -m pip install -r requirements.txt
$ python main.py
Additional Informations
General Informations:

If you find any malfunction, contact me on Discord: SenT#0417.
Example
verification_example.png

Credits
SenT.
