from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "<h1>Welcome to My Hemant  Website</h1><p>This is my first site.</p>"

if __name__ == "__main__":
    app.run(host="0.0.0.0",port=5000,debug=True)
