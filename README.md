# flaskTest

## Setting up and running the Flask app

1. Clone the repository:
   ```
   git clone https://github.com/Prof-Basseem/flaskTest.git
   cd flaskTest
   ```

2. Create a virtual environment and activate it:
   ```
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required dependencies:
   ```
   pip install flask
   ```

4. Run the Flask app:
   ```
   python app.py
   ```

## Project Structure

```
flaskTest/
│
├── app.py
├── templates/
│   └── index.html
└── README.md
```

## Deploying to Heroku

1. Install the Heroku CLI:
   ```
   https://devcenter.heroku.com/articles/heroku-cli
   ```

2. Log in to your Heroku account:
   ```
   heroku login
   ```

3. Create a new Heroku app:
   ```
   heroku create
   ```

4. Deploy the app:
   ```
   git push heroku master
   ```

5. Open the app in your browser:
   ```
   heroku open
   ```
