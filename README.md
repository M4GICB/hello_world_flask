# My First Flask Web App: hello_world_flask

## Description:
This is a basic web application that has a home page and an about page. The home page is routed to `localhost:5000/` and `localhost:5000/home`. The about page is routed to `localhost:5000/about`. This is a basic proof of concept project that shows how to set up a python Flask web application for learning purposes.

Tutorial Being Followed: Corey Schafer Flask Tutorial - https://youtube.com/playlist?list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH

## Set Up:
### Requirements:
1. Python
2. Pip
3. Flask
4. A text editor

### Steps
#### 1. Install Python
1. First check if python is installed or not by opening your terminal and typing the following command.
```
python --version
```  
2. If python is properly installed your output should look like:
```
Python 3.8.5
```

3. If your version of python is earlier than this, you need to install the latest version of python.
4. Install python: https://www.python.org/downloads/

#### 2. Install Pip
1. First check if pip is properly installed or not by opening your terminal and typing the following command:
```
pip --version
```

2. If python is properly installed your output should look like:
```
pip 20.3.3
```

3. If your version of pip is earlier than this, you need to install the latest version of pip.
4. Install Pip: https://pip.pypa.io/en/stable/installing/

#### 3. Install Flask
1. First check if Flask is installed or not by opening your terminal and typing the following command.
```
flask --verison
```
2. If Flask is properly installed your output should look like:
```
Python 3.8.5
Flask 1.1.2
Werkzeug 1.0.1
```

3. If your version of flask is earlier than this, you need to install the latest version of flask.
4. Install Flask by running the following command:
```
pip install flask
```
5. Make sure Flask installed correctly by starting up python and importing flask
  1. Open your terminal
  2. start python by typing the following command:
  ```
  python
  ```
  3. Python should now start and your terminal will have a `>>>` infront of your cursor
  4. Type the following command and hit `enter`
  ```
  import flask
  ```
  5. If this runs with no errors then flask is installed properly. If errors occur, flask needs to be properly installed.
    * See https://flask.palletsprojects.com/en/1.1.x/installation/ for further installation documentation.
  6. Type the following command to exit the python editor in your terminal
  ```
  exit()
  ```

## Running The Web App
### 1. Clone this repo
### 2. Navigate to the directory (within the terminal) where you saved this repo
### 3. Set an environment variable to the file that will be the Flask application.
* In our case, run the following command for linux/mac
```
export FLASK_APP=HelloWorld_Flask.py
```
* For windows run
```
set FLASK_APP=HelloWorld_Flask.py
```
### 4. Run the application with the folowing command
```
flask run
```
### 5. If there are no errors, your output should look like the following:

```
* Serving Flask app "HelloWorld_Flask.py"
* Environment: production
  WARNING: This is a development server. Do not use it in a production deployment.
  Use a production WSGI server instead.
* Debug mode: off
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```

### 6. Open your web browser and navigate to the site provided in the final line of the output message
 * You can also replace the `127.0.0.1` with `localhost`
 * eg. instead of navigating to http://127.0.0.1:5000/ you can navigate to http://localhost:5000/
