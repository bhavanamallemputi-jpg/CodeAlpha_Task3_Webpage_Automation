# CodeAlpha Task 3 - Automated Webpage Title Extractor

## Project Overview

This project was developed as part of the CodeAlpha Internship Task 3:
Task Automation with Python Scripts.

The project automatically extracts the title of a webpage using Python
and saves the extracted information into a text file.

## Objective

The objective of this project is to demonstrate how Python can be used
to automate a repetitive web-based task.

## Technologies Used

- Python
- Requests
- BeautifulSoup
- Google Colab

## How It Works

1. The program takes a webpage URL.
2. It sends a request to the webpage.
3. It retrieves the HTML content.
4. BeautifulSoup parses the HTML.
5. The webpage title is extracted.
6. The extracted title is saved into a text file.

## Example

Website:

https://www.python.org/

The program extracts:

Welcome to Python.org

and saves the result in:

webpage_title.txt

## Project Files

- `CodeAlpha_Task3_Webpage_Automation.ipynb` - Complete Google Colab project
- `webpage_title.txt` - Generated output
- `requirements.txt` - Required Python libraries
- `README.md` - Project documentation

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
