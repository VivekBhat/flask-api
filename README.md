# Basic API using Flask

## Setup the project

* SetUP a working directory:
    
    `$ mkdir flask-by-example && cd flask-by-example`

* Initialize a new git repo within your working directory:

    `$ git init`

* Set up a virtual environment to use for our application `(add to gitignore)`:

    ```
    $ python3 -m venv env
    $ source env/bin/activate
    ```

* You should now see you (env) to the left of the prompt in the terminal, indicating that you are now working in a virtual environment.

    ```
    In order to leave your virtual environment, just run deactivate, and then run source env/bin/activate when you are ready to work on your project again.
    ```

* Next we’re going to get our basic structure for our app set up. Add the following files to your “flask-by-example” folder:

    ```
    $ touch app.py .gitignore README.md requirements.txt
    This will give you the following structure:

    ├── .gitignore
    ├── app.py
    ├── README.md
    └── requirements.txt
    ```


## Run the app

* Next install Flask:
  ```
  $ python -m pip install Flask==1.1.1
  ```
* Add the installed libraries to our requirements.txt file:
    ```
    $ python -m pip freeze > requirements.txt
    Open up app.py in your favorite editor and add the following code:
    ```

* Run the app:

    `python app.py`

    And you should see your basic “Hello world” app in action on http://localhost:5000/. Kill the server when done.


    