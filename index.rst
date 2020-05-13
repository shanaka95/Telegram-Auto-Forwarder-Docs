===============
Telegram Auto Forwarder
===============
***************
Requirements
***************

Required Software
===============


You need to install following software on your compuer, Before using this bot.

Git - https://git-scm.com/downloads

Heroku CLI - https://devcenter.heroku.com/articles/heroku-cli#download-and-install

Python3 -  https://www.python.org/downloads/

Python Dependencies
===============

Open CMD in side your project directory.

Run Following command to install required dependencies

.. code-block:: bash

   python3 -m pip install -r requirements.txt

*****************
First Step - Authenticating Locally
*****************


After Installing all the required Software and Dependencies,You need to run the bot on your computer at least once.

Open CMD in your project directory and run below command,

.. code-block:: bash


   python3 test3.py

It will ask a Phone number or Bot token from you.Enter your Telegram Enabled phone number.
Then they will send you OTP code to your telegram app or as a SMS. Enter it in CMD when it asks

*****************
Second Step - Upload to Heroku
*****************

Login to Heroku
===============

This is not an essential step, But if You asked to login to Heroku when your try to execute git commands given below, Please execute this command

.. code-block:: bash


   Heroku login

It will ask to Press any key.After pressing a key a web browser tab will be opened.Login with your Heroku Account username and password.Then close browser window.

When you logged in using Browser windows, CMD will automatically display 

.. code-block:: bash

   Logged in as <Your email>
