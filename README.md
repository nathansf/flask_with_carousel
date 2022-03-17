git clone https://github.com/NathanSF/flask_with_carousel.git

cd flask_with_carousel

# Create virtualenv
virtualenv env

source env/bin/activate

# Install reqs
pip install -r requirements.txt

# Run it
python urls.py 

# In browser go to page
http://127.0.0.1:5000/


+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
UPDATED FOR PYTHON 3.9.x	    Steve Malikoff (1944GPW)

## Get repo
C:\>cd \users\you\source\repos
C:\>cd \users\you\source\repos>git clone https://github.com/NathanSF/flask_with_carousel.git

C:\>cd \users\you\source\repos>cd flask_with_carousel

## Create virtualenv
C:\>cd \users\you\source\repos\flask_with_carousel>python -m venv venv

## Set FLASK_APP variable to start py module and activate
C:\>cd \users\you\source\repos\flask_with_carousel>flask_env.bat

## Install reqs (just use latest modules)
(venv) C:\>cd \users\you\source\repos\flask_with_carousel>pip install -r requirements.txt

## Run it
(venv) C:\>cd \users\you\source\repos\flask_with_carousel>flask run
 * Serving Flask app 'urls' (lazy loading)
 * Environment: development
 * Debug mode: on
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 123-456-789
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

## In your browser go to
http://127.0.0.1:5000/
