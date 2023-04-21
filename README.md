# Shakespeare-s-Plays
Web-Scraping

# Shakespeare's Plays Text Analysis
This is a Python program that downloads text files of Shakespeare's plays from a given URL(http://www.textfiles.com/etext/AUTHORS/SHAKESPEARE/), and performs various analyses on the text.

# Requirements
To run this program, you need to have Python 3 installed on your system. You also need to install the following Python packages:
requests
BeautifulSoup

## You can install these packages using pip:
pip install requests BeautifulSoup4

# The program will perform the following tasks:
1) Download the first 5 text files of Shakespeare's plays from the given URL.
2) Get all { file name : { line number : number of words in the line } } combinations in a dictionary.
3) Find the number of lines with more than 10 words in each file.
4) Find the number of words spoken by each character in all the plays.
5) Find the 10 most common words spoken by each character.
6) Find the size, last modified datetime, and absolute path of each file, and store the information in a CSV file.
