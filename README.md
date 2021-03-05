# One minute Pitch
* Author 
* Jackson Ikonya

## Description
* This is a flask application that allows users to post one minute pitche and also allow other users who have signed up to comment. It also allows a person to sign up to be able to access the functionalities of the application,

## LIve Link

## User Story
* Comment on the different pitches posted py other uses.
* See the pitches posted by other uses.
* Vote on s pitch they have viwed by giving it a upvote or a downvote.
* Register to be allowed to log in to the application
* View pitches from the different categories.
* Submit a pitch to a specific category of their choice.

## Development Installation
To get the code..

1. Cloning the repository:

2. Move to the folder and install requirements
cd minute-pitch
### create virtual environment and install pip
$ python3 -m venv --without-pip virtual
$ source virtual/bin/env
$ curl https://bootstrap.pypa.io/get-pip.py | python

pip install -r requirements.txt

3. Exporting Configurations
export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
4. Running the application
python3.8 manage.py server
5. Testing the application
python3.8 manage.py test
Open the application on your browser 127.0.0.1:5000.

## Technology used
* Python3.6
* Flask
* Heroku
## Known Bugs
There are no known bugs currently but pull requests are allowed incase you spot a bug
## Contact Information
If you have any question or contributions, please email me at []

## License
MIT License:
Copyright (c) 2021 Jackson Ikonya 