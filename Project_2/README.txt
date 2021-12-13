Tarek Elbendary
TAEZKV
14289447
Networks Project Documentation

This program was created in python. I used python 3.8 to run this project, however other versions might possibly work as well

To run this program:

Open two terminals, and navigate to the project folder directory containing the files project.py, users.txt, and README.txt

On the first terminal, run the project.py program with no additional sys args to instantiate the server
on the windows operating system this can be accomplished with the following command:
project.py

On the second terminal, run the project.py program with a sys arg of localhost:19447 to instantiate a client
on the windows operating system this can be accomplished with the following command:
project.py localhost:19447

Once the client is instantiated, it should connect to the server with an ip address and port.
From here, simply enter any of the following user commands in the client terminal:
login <username> <password>
logout
send all <message>
send <username> <message>
newuser <username> <password>
who

kill the terminals to terminate the client/server instances
