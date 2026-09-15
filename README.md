vino
====

An application that shows a wall of popular posts, or posts from a specified tag.

Includes a python library for the [Vine.co (Trellis because it uses Vine's) API format](https://github.com/starlock/vino/wiki/API-Reference)

## Quick start


Clone the repo and move into that folder

    git clone git://github.com/migbrunluz2/vino-trellis.git
    cd vino
    pip install -r requirements.txt

Setup your Trellis username and password (in order to have a Trellis account you need to sign up at trls.uk and apply to join.)

    export VINO_USER="your_username_here"
    export VINO_PASSWORD="your_password_here"

On Windows,you use

set VINO_USER=your_username_here
set VINO_PASSWORD=your_password_here

Start the server

    python app.py

Requirements has been changed up a bit to be compatible with newer versions of Python.

## Tests


To run the tests, you need `nose` and `mock`. Just run

    nosetests
