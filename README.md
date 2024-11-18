# version-control-exercise

## setup

Todo: create and activate a virtual environment 
```sh
conda create -n reports-env-2024 python=3.12
```

Activate the environment (whenever you come back to this project):

```sh
conda activate reports-env-2024
```
Todo: install packages
```sh
pip install -r requirements.txt
```
[Obtain an API Key](https://www.alphavantage.co/support/#api-key) from AlphaVantage.

Create a ".env" file and add contents like the following (using your own AlphaVantage API Key):

```sh
# this is the ".env" file:
ALPHAVANTAGE_API_KEY="..."
```

## usage

run the example code

```sh
python app/my_script.py
```

Run the unemployment report:

```sh
#ALPHAVANTAGE_API_KEY="..." python app/unemployment.py
python -m app.unemployment
```
Run the stocks report:

```sh
python -m app.stocks_report
```

### web app
Run the web app (then view in the browser at http://localhost:5000/):
```sh
FLASK_APP=web_app flask run
flask run
```

## Testing

Run tests:

```sh
pytest
```