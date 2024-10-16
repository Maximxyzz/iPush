# iPush
This Python Pushbullet GUI script allows you to connect your mobile device to Ubuntu, displaying real-time notifications through an easy interface. It offers device pairing, connection status tracking, and notification syncing.


Requirements:

pip install pushbullet.py
pip install tkinter


You must have Pushbullet set up and have the API key (Access Token).
Python 3 must be installed in your virtual environment.


 
Explanation:

API Key Input: The user provides their Pushbullet API key through a text input field.
    

Pshbullet Connection: 
    
When the user clicks "Connect", the script will authenticate with Pushbullet using the provided API key.


Show Notifications: 

Clicking "Show Notifications" retrieves the latest pushes from the Pushbullet account and    displays the notification titles and bodies in a text area.

    
evice List: Once connected, the devices connected to the Pushbullet account will be listed.
