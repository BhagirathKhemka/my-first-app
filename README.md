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
python app/unemployment.py
```
Run the stocks report:

```sh
python app/stocks_report.py
```