# Electronic Messaging Platform
> This project uses Python 3.6
> 
![image](https://user-images.githubusercontent.com/70169625/199143248-c09ab16c-f1e6-4828-83dd-803e99774ebd.png)
> 
> You can also access to the project in the cloud. This is the [page](http://odardila.pythonanywhere.com/)

## Table Of Contents:
 - [Description](#description)
 - [Installation](#installation)
 - [Contributing](#contributing)

## Description
In order to access the platform, the user must register by providing the following data:
- User name.
- E-mail address.
- Password.
Upon registration, a link to activate the account must be sent to the e-mail address entered.

Once the access user to the platform has been created, the end user will have the possibility of:
- Activate their account using the link sent to the email entered during registration.
- Login to the platform using the credentials with which he/she registered. The user will only be able to log in once his account has been activated.
- Request the recovery of your password. To do so, you must enter the e-mail address with which you registered and you will be sent a link to recover your password.
- Change your password by entering the password recovery link sent by mail. In this link you must enter and confirm your new password, and if they are the same, the password will be updated.

After logging into the platform, the user will be able to:
- Send messages to other users. To do this, it is necessary to enter the user to whom the message will be sent (this user must exist), a subject and the body of the message.
- Read messages received from other users. The display of these must show the subject, the user who sent it, the date it was sent and the body of the message.

And for the development of the project:
- Outlook SMTP will be used to send account activation and password recovery emails. For this, it is necessary to use your Uninorte account.
- The database must be relational.
- User passwords must be stored securely.
- The connection to the server must be secure.
- A CSS library must be used to handle the styles of your application.

## Installation
1. Clone or download de repository:
    ```
    $ git init
    $ git clone https://github.com/oardilac/Hangman_game.git
    ```

2. Open the console inside the project directory and create a virtual environment.
    ```bash
    $ py -m venv venv
    $ source venv/Scripts/activate
    ```

3. Install the framework that the program needed
    ```
    $ pip install -r requirements.txt
    ```

4. Run the program
    ```
    $ flask run
    ```

## Contributing
Pull requests are welcome! For major refactors, please open an issue first to discuss what you would like to improve. Feel free to create a fork of this repository and use the code for any noncommercial purposes.
