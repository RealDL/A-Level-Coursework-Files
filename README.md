# A-Level-Coursework-Files
This is all the code from the different versions of my game Bullet Assault in Python. These are updated versions of my game that I am making.

# Pre-set up:
1. Install python IDLE [here](https://www.python.org/downloads/).
2. Make sure you install it **with path** otherwise installing external modules will be very difficult.
3. run `pip install pygame` in cmd or powershell.
4. run `pip install rsa` in cmd or powershell.
5. run `pip instsall pycryptodome` in cmd or powershell.
6. Make sure that your filewall has enabled python for private and public so that other computers on your local network can join the server. Note - when you run the server.py code a firewall message will pop up. Make sure you press **allow** as that will then mean clients can connect to the server. Otherwise, no clients can connect via LAN on other computers.

# Set up:
1. Download this repository.
2. Extract it all.
3. You do not need to edit the settings.py script or any script, but you can if you know what you're doing because the clients will only need to enter the IP Address of the server into the textbox.
4. You will need to run `ipconfig` in cmd or powershell to determine the server IP address. Clients can then enter the server IP into the textbox and join the server.

# How to run:
1. First run an instance of server.py with `py server.py` on cmd or powershell or python IDLE it doesn't really matter.
2. Now you can run as many instances of client.py with `py client.py` on cmd or powershell or python IDLE it doesn't really matter.
3. Now you can play with it and have fun with friends!

# Notes
1. The code has been designed to be a bullet proof simple method to host as many players on a server as you would like.
2. The encryption used is asymmetric encryption to exchange a symmetric key to establish a secure connection between the client and server.
3. Finally, if you need any help feel free to message me if you find any errors or you are struggling to set this up. My Discord is @realdl

# Thank you. 🙏
Thank you for reading this. Feel free to check out my other repositories.
