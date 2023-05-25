# first install ec2

# install python,pip using below commands

yum install python3

yum install python3-pip

# create one file inside ec2 flask.py copy below code

from flask import Flask

app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello, World!'

if __name__ == '__main__':
    app.run()


# run the application python3 flask.py