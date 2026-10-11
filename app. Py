from flask import Flask
app = Flask(__name__)

@app.route("/")
def home():
    return """
    <html><head><style>
    body{font-family:Arial; text-align:center; background:#f0f0f0; padding:20px}
    .box{background:white; padding:20px; border-radius:10px; max-width:600px; margin:auto}
    h1{color:green}
    button{padding:10px 20px; background:green; color:white; border:none; border-radius:5px}
    </style></head><body>
    <div class='box'>
    <h1>CYBERLEARN-NG</h1>
    <p><b>Barka da zuwa!</b></p>
    <p>Sunana Umar Shehu - Zaria, Kaduna</p>
    <p>Wannan shine website na na farko na koyar da Cyber Security</p>
    <hr>
    <h3>Darussa:</h3>
    <p>Lesson 1: Menene Hacking?</p>
    <p>Lesson 2: Menene Termux?</p>
    <p>Lesson 3: Yadda ake kare kanka</p>
    <br><a href='/about'><button>Game da mu</button></a>
    </div></body></html>
    """

@app.route("/about")
def about():
    return "<h2 style='text-align:center'>Game da mu</h2><p style='text-align:center'>CyberLearn-NG na Umar ne.<br><a href='/'>Koma Gida</a></p>"

if __name__ == "__main__":
    app.run(host="0.0.0.0", port=10000)
