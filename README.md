# Demo Flask
This project uses Python 3.6.

## Dependencies
To install the required dependencies, please follow these steps:

1. Open a console.
2. Go to the project directory (with `cd` command).
3. Write and execute `pip3 install -r requirements.txt`.

## Initializate DB
To run the app, you need to provide a Microsoft account for the app to send/receive emails. To add this account follow these steps:

1. Open the file `schema.sql`.
2. Locate the line `INSERT INTO credentials (name,user,password) VALUES ('EMAIL_APP','developmentcapstone', '$TR41NC0URS3R4$')`.
3. Replace `developmentcapstone` with the email address.
4. Replace `$TR41NC0URS3R4$` with a password to access the email account.
5. Run `flask init-db` on the project directory.

## Run application
For run the app you need to use `flask run` on the project directory.

# Hangman_game
> Python Hangman
> 
![image](https://user-images.githubusercontent.com/70169625/198852457-7bbb37cc-72af-41f3-9aa9-cec1e939b5be.png)


## Table Of Contents:
 - [Description](#description)
 - [Installation](#installation)
 - [Contributing](#contributing)

## Description
It is the typical hangman game made in python 3, which allows you to guess the word, and can be used in different ways, such as entertainment, educational, etc...

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

3. Run the program
    ```
    $ py hangman.py
    ```

## Contributing
Pull requests are welcome! For major refactors, please open an issue first to discuss what you would like to improve. Feel free to create a fork of this repository and use the code for any noncommercial purposes.