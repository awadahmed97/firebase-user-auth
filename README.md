Hi Guys!
This is a basic Flask + firebase authentication Demo.

You will need to setup a firebase account and create a n ew project.
Clone the project, Then

1. run the following command in your terminal:
   pip3 install -r requirements.txt
2. Open the project in your text editor and go to the app/routes.py file.
3. Update the values in the config object with you firebase project credentials
4. Then run the command flask run
5. You should be able to register, get a password verification link and log in.


I have not added sessions into the routes.py file yet however this code should be sufficient enough to
easily integrate to firebase.
