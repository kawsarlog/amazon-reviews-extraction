# Amazon Reviews Extraction Script

[![Python Version](https://img.shields.io/badge/python-3.9-blue)](https://www.python.org/downloads/release/python-390/)
[![Requests Version](https://img.shields.io/badge/requests-2.31.0-brightgreen)](https://pypi.org/project/requests/)
[![Pandas Version](https://img.shields.io/badge/pandas-1.2.0-orange)](https://pypi.org/project/pandas/)
[![BeautifulSoup Version](https://img.shields.io/badge/bs4-0.0.1-lightgrey)](https://pypi.org/project/bs4/)
[![lxml Version](https://img.shields.io/badge/lxml-4.9.2-green)](https://pypi.org/project/lxml/)

## Description
🛍️📊 Simplify Amazon product review extraction with this Python script. By utilizing the `requests`, `pandas`, `bs4`, and `lxml` modules, the script effortlessly retrieves and parses HTML content from review pages.

The exported data follows this format:
|   Name    | Stars |             Title             |    Date    |                  Description                  |
|:---------:|:-----:|:-----------------------------:|:----------:|:----------------------------------------------:|
|   Jeff    |  4.0  | Rugged, good look and nice fit| 02/10/2018 | The short answer to if you should go down from...|
| M. Burke  |  5.0  |     My Favorite Jacket       | 19/04/2023 | I went through the most recent winter with thi...|
|   Jake    |  4.0  |    Decent shirt jacket       | 27/04/2023 | I’ve been wearing this regularly for about an m...|
|  joe j    |  4.0  | Not bad. It's a good light...| 05/04/2023 | It's not really a jacket and not really a overs...|
|Jorge Risco|  5.0  | Muy buen material, abriga...| 24/05/2023 | Muy buen material, para mi que vivo en el sur .|
|...        |       |                             |            |                                                |


## Prerequisites
- Python 3.9
- requests 2.31.0
- pandas 1.2.0
- bs4 0.0.1
- lxml 4.9.2

## Python Installation
Before running the Funda Scraper, ensure that you have Python 3.9.7 installed on your system. To check the Python version, open a terminal (or command prompt) and enter the following command:

```bash
python --version
```

If Python 3.9.7 is not installed, you can download it from the official Python website: [Python Downloads](https://www.python.org/downloads/release/python-397/)

Make sure to add Python to your system's PATH variable during the installation. Here's a helpful image to guide you:

![Add Python to PATH](https://camo.githubusercontent.com/96c8ee1f0cc3bbb4145befc07d39dfc629404b8f3dc692298b6419e20714fa33/68747470733a2f2f696d673030312e70726e747363722e636f6d2f66696c652f696d673030312f544e2d6d62647a79547871767130546a6f7a683959512e6a706567)

## Script Installation
1. Clone the repository: `git clone https://github.com/kawsarlog/amazon-reviews-extraction.git`
2. Navigate to the project directory: `cd amazon-reviews-extraction`
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage
1. Modify the script to specify the Amazon product URL and desired parameters.
2. Run the script by executing the following command:

   ```
   python amazon_reviews_extraction.py
   ```

3. The extracted reviews will be saved in a CSV file.

For a detailed tutorial on how to use this script, please refer to the [Amazon Reviews Extraction Tutorial](https://www.youtube.com/watch?v=m-3kyQLIXlU).
[![amazon reviews scrape](https://img001.prntscr.com/file/img001/5dJtVNx6T6eoizkcI4n3Dg.png)](https://www.youtube.com/watch?v=m-3kyQLIXlU)

## Contact
For any questions or feedback, feel free to reach out:

- Email: kawsar@kawsarlog.com
- Website: kawsarlog.com

---

**Note:** This script should be used responsibly and in compliance with Amazon's Terms of Service. The script is for educational purposes only.
