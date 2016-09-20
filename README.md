# FREAK
Contains code for the FREAK Project (<b>F</b>acial <b>R</b>ecognition <b>E</b>lectromagnetic <b>A</b>rduino - loc<b>K</b>)


You can change the algorithm used for face recognition by editing the face_learn.py and facerecog.py .

face_detect.py stores the face of person in pics folder. Make the folders in pics folder before running the program. Instructions given in Readme.md inside /pics

First detect and store the face using face_detect.py
  -Pressing 'space' will store the face
  -pressing 'TAB' will change to next person
  -pressing 'a' will go back to previous person
  -pressing 'ESCAPE' will end the program.
Atleast store ~50 faces for everyperson

After the faces have been stored, use face_learn.py to learn the faces of everyone. This will create trainer.xml file.

Then facerecog.py can bet kept in the rasbery pi with the haarcascade_frontalface_alt_tree.xml and trainer.xml file and run

Remember to change the IP address in facerecog.py to the IP Address of server.
Make sure that the server is accisible.

Server code is yet to be uploaded.
