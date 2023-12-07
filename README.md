# utils
## Currency Converter

- works with weird inputs:
![even weird inputs will work](img/currency_converter_00.png)

- different currencies
![different currencies](img/currency_converter_01.png)

- nice look
![nice look](img/currency_converter_02.png)

- no need in ".py" extension - just name of the script
![no need in .py extension](img/currency_converter_03.png)

### Installation:
- git clone repo
- create & activate virtual environment:
  ```Python3
  python3 -m venv venv
  source venv/bin/activate
  ```
- pip-install 3 required modules:
  ```Bash
  pip install -r requirements.txt
  ```
- get free API Key @ https://app.freecurrencyapi.com/
- write it to .env file:
  ```Bash
  TOKEN=<your API Key> # no symbols like '"' or '<>' required and mind "no spaces"
  ```
  
- start script:
  ```Bash
  ./currency_converter
  ```
