# hello-world-flask.io
hello world flask



# setting up flask
 from the command line type pip install flask
 
 # create a hello-world-flask repo
 One you are done installing flask
 create a directory *mkdir name of directory*
 inside your directory create *app.py*
 
 # open your app.py in the text editor
 from flask import Flask,

app = Flask(__name__)

@app.route("/")

def main():
	return "Hello world!"
if __name__ == '__main__':
    app.run()
    
# Run your app
python app.py

# wooow
you just made your first web app using flask
