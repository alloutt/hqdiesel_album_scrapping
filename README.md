
## Steps to install:
### 1.Create python venv
```python
python -m venv hqdiesel-scraper
```
### 2.Click on bs4.bat
A terminal will get opened like
`(hqdiesel-scraper) C\...\hqdiesel-scraper>`
```
pip install -r requirements.txt
```
### 3.Running script
```
python scrape.py
```
took reference from this repo for main code(https://github.com/falcon883/hqdiesel-album-scraper)

## Extra Details

### scrape_photoshoots_only.py 
**Purpose** : It will filter photoshoot only albums from given range of albums mentioned inside the script file and download automatically.

*Don't forget to edit range inside script*

### get_photoshoot_urls.py
**Purpose** : It will print only photoshoots album urls on console without downloading.

*to save urls in file*
```
python get_photoshoot_urls.py >> photoshoot_urls.txt
```

### check_female.py
**Purpose** : Filters links for only female photoshoot albums.(*you can edit url inside script for custom filter,refer hqdiesel website.*)

*to save urls in file*
```
python check_female.py >> female_photoshoot_urls.txt
```

### get_names.py
**Purpose** : Checks urls got from `get_photoshoot_urls.py` and print names,file no. and pages no. into a csv file.

### Search_female.bat 
Searches album details by name

### Random.bat
Just a Pseudo-random number generator `range:1-540`*editable*

### cleanup.bat
Cleans the Downloaded Photoshoot Folders

### bs4.bat
Just a faster venv launcher

### Data
Contains data extrated during testing
