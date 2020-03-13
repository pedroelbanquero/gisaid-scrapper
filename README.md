# GISAID scrapper
Scrapping tool for GISAID data regarding SARS-CoV-2. You need an active account in order to use it. 

Your login and password should be provided in `credentials.txt` file in format:
```
login
password
```

The tool was written for personal use, so little to no maintenance is to be expected.

## Usage
`python3 gisaid_scrapper_headless.py` should run the scrapper in headless mode. If you need a browser window, you can specify it 
by changing `True` to `False` in the line `scrapper = GisaidCoVScrapper(False)`

## Result
The whole genom sequences from GISAID will be downloaded into `fastas/` directory.
