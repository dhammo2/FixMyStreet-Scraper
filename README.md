# FixMyStreet-Scraper

## Description

This repository contains a python package for the automated scraping of the FixMyStreet.com reporting service.

Whilst our best efforts have been made to ensure that the package is robust, as with any web scraping tasks,  if the website structure changes the package will no longer function as intended. We will however endeavour to do our best to update the package as soon as an issue is raised. 

> **_DISCLAIMER:_** This code was developed for academic purposes. Using this software package may be a violation of the terms of use set out by FixMyStreet.com. By downloading and using this package you do so at your own legal risk.

### Compatibility
This code should be compatible with all websites website using the FixMyStreet platform. The following websites have been tested and confirmed compatible. 

1. https://fixmystreet.com
2. https://zueriwieneu.ch/
3. https://fixamingata.se/
4. https://fixmystreet.ie/
5. http://www.fiksgatami.no/

## Requirements

- Python 3

## Installation

### Using PIP

``` pip install fms-scraper ```

### Manual Installation

## Usage

```python

#Import the Package
import fms-scraper

#Set the Working Directory either by
     # (a) Using
     import os
     os.chdir(“PATHTOWD”)
     # (b) Running the script through the command line

#Call the Scraping Function
ScrapeFMS(continuous = False, images = True)


```

### Options

1. Set ```continuous = True``` to wait and continue scraping when all currently published reports have been scraped or set ```continuous = False``` to stop the web scraping process when all currently published reports have been obtained. 
2. Set ```images = True``` to download all images posted in reports and updates. 


### Citing This Package
Please accredit this package by citing the following in your references. 

```
@phdthesis{hammocks_2019, title={Horizon Scannong Through Automated Information Prioritisation}, author={Hammocks, Daniel}, year={2019}}
```
