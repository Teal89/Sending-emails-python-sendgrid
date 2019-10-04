# Sending-emails-python-sendgrid
Sending emails in Python with Sendgrid (Twilio)

Requirements:

Python 2 or 3 
Sendgrid account
Sendgrid Python Library

Steps to run:

Install Virtualenv package: https://virtualenv.pypa.io/en/latest/installation/

Run 

virtualenv emails

Activate VM 

source ./emails/bin/activate

Install Sendgrid python helper library

pip install sendgrid


Reminders:

Ensure that SENDGRID_API_KEY environment variable is set. 
Not sure how to set environment variables? See: https://www.twilio.com/blog/2017/01/how-to-set-environment-variables.html

Excecute file by running:

python send_email.py
