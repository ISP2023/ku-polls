# Web Polls for Kasetsart University

*ISP STUDENTS: You can copy the STRUCTURE of this file but not the TEXT*

An application for conducting a poll or survey with multiple-choice questions, written in Python using Django. It is based on the [Django Tutorial project][django-tutorial], and adds additional functionality.

A polls application for [Individual Software Process](https://cpske.github.io/ISP) course at [Kasetsart University](https://ku.ac.th).

## Requirements

Requires Python 3.8 or newer.  Required Python packages are listed in [requirements.txt](./requirements.txt). 

## Install and Configure the Application

See [Installation](../../wiki/Installation) in the project wiki.


## Running the Application

1. Start the server in the virtual environment. 
   ```
   # activate the virtualenv on Linux and MacOS
   source env/bin/activate
   # on MS Windows:
   env\Scripts\activate

   # run the django server
   python3 manage.py runserver
   ```
   This starts a web server listening on port 8000.

2. You should see this message printed in the terminal window:
   ```
   Starting development server at http://127.0.0.1:8000/
   Quit the server with CONTROL-C.
   ```
   If you get a message that the port is unavailable, then run the server on a different port (1024 thru 65535) using
   ```
   python3 manage.py runserver 12345
   ```

3. In a web browser, navigate to <http://localhost:8000>

4. To stop the server, press CTRL-C in the terminal window. Then exit the virtualenv by closing the window or by typing:
   ```
   deactivate
   ```

## Demo User Accounts

Sample polls and users data are included. 

* `demo1` password `Hackme1`
* `demo2` password `Hackme2`

## Project Documents

All project-related documents are in the [Project Wiki](../../wiki/Home)

- [Vision Statement](../../wiki/Vision%20Statement)

- [Requirements](../../wiki/Requirements)

- [Development Plan](../../wiki/Development%20Plan)

- [Iteration 1 Plan](../../wiki/Iteration%201%20Plan) and [Task Board](../../projects/1)


[django-tutorial]: https://docs.djangoproject.com/en/3.1/intro/tutorial01/

