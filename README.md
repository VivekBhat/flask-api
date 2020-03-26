* First things first, let’s get a working directory set up:
    
    `$ mkdir flask-by-example && cd flask-by-example`

* Initialize a new git repo within your working directory:

    `$ git init`

* Set up a virtual environment to use for our application:

    ```
    $ python3 -m venv env
    $ source env/bin/activate
    ```

* You should now see you (env) to the left of the prompt in the terminal, indicating that you are now working in a virtual environment.

    ```
    In order to leave your virtual environment, just run deactivate, and then run source env/bin/activate when you are ready to work on your project again.
    ```

Next we’re going to get our basic structure for our app set up. Add the following files to your “flask-by-example” folder:

```
$ touch app.py .gitignore README.md requirements.txt
This will give you the following structure:

├── .gitignore
├── app.py
├── README.md
└── requirements.txt
```
