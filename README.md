# Password-Generator
Password Generator Project where User can set Password Length and choose type of characters to include in the Generated Password

This will be an AWS ubuntu EC2 based instance project. It is assumed that the ubuntu EC2 instance is already running with docker engine installed.This is a python based web project. It will have a field to set length of generated password. The User will also have the option to check/uncheck boxes to Include or exclude UpperCase, LowerCase,Digits and or Special Characters/symbols.

Later versions of this project will include a database to save generated passwords.


Docker commands
# Build the image
docker build -t password-web-app .

# Run the container
docker run -d -p 5000:5000 --name passwordgen password-web-app
