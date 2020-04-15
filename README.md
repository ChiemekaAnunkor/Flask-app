# Flask-app
f=
from flask import Flask

app2 = Flask(__name__)


@app2.route('/<name>')
def index(name):
	return '<hi>hello {}!<hi>'. format(name)
