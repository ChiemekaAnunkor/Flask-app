# Flask-app
from flask import Flask

app2 = Flask(__name__)


@app2.route('/')
def index():
	return '<hi>hello {}!<hi>'. format()
