# ECS Execute Command Helper Utility

Got tired of executing one command after another to finally exec into an ECS Fargate task. 

This interactive utility walks you through it and launches the session for you. 

# Windows Support

To run the script in windows you have to replace the following file into your Python Lib.

Windows\simple_term_menu.py file is present in this repo.

this file need to be replaced in the following location in your system.
"Users\{YOUR_USER_NAME}\AppData\Local\Programs\Python\Python312\Lib\site-packages"

# TroubleShooting

If you get the following error, while running the script.

Unable to start command: Failed to start pty: fork/exec /bin/bash: no such file or directory

You can try another shell like /bin/sh or /bin/csh. 
So change the "bin/bash" to the "bin/sh" or whichever related to your container's Shell.