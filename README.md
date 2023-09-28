 # WEBPAGE SCRAP EASY BY PYTHON(CS 50 FINAL PROJECT)

# Video Demo:  <https://youtu.be/PHWIiXJaNv8>

# Description:
In today's data-driven world, web scraping has become an essential skill for extracting valuable information from websites. However, the process of scraping web data can be tedious and time-consuming, especially when dealing with multiple URLs and analyzing their responses. To simplify this task, I have developed a Python project for my "Harvard CS50 Introduction to Programming with Python" course that offers a user-friendly solution to web scraping
for "Harvard CS50 Introduction to programming with Python." The project aims to streamline website scraping by providing users with essential information about the websites they input. The tool simplifies the process of understanding website characteristics, such as response codes and page sizes, by displaying them in an easy-to-read format.

# Features:

URL Input: The user can input one or more URL addresses they wish to analyze. The program accepts a list of URLs as input.

Request and Response Monitoring: The Website Analysis Tool initiates requests to each URL provided and captures the corresponding responses. By doing so, it efficiently tracks the web servers' response codes, indicating the status of the request (e.g., 200 for success, 404 for not found, etc.).

Page Size Calculation: After successfully receiving the responses, the tool calculates the sizes of the web pages associated with each URL. This information is vital for understanding website performance and optimizing load times.

Comment Line and Directory Identification: The tool goes beyond standard response codes and page sizes. It also identifies and highlights comment lines and directories on the web pages. This feature assists users in quickly grasping the page's structure and content, facilitating efficient website scraping.

User-Friendly Interface: The Website Analysis Tool offers a straightforward and intuitive interface, making it accessible to users of all levels of expertise. The results are displayed in a well-organized format for easy interpretation.

 # How It Works:

User Input: The user provides one or more URLs they want to analyze, either through direct input or a file containing the URLs.

Sending Requests: The program sends requests to the URLs and records the responses, noting the status codes received.

Analyzing Page Sizes: After receiving the responses, the tool calculates the sizes of the web pages associated with each URL.

Identifying Comments and Directories: Using intelligent parsing and pattern recognition algorithms, the tool identifies and presents comment lines and directories on the web pages, enhancing the user's understanding of the website's structure.

Displaying Results: The Website Analysis Tool displays the response codes and page sizes for each URL in a well-organized format. Additionally, it highlights comment lines and directories, making it easier for users to glean crucial information.
This is my final project for "Harvard CS50 Introduction to programming with Python". This project makes websites scraping easier. You can see quickly the comment lines or directories which the page has.

This project will also print requests and responses for you. From the URL addresses that you gave as an input, it will print the website response code from the URL link and the page sizes.
## Installation & Use
1. Clone the code.
1. Run the command `pip install -r requirements.txt` in the app directory.
2. Than run it: `python3 ./project.py -u https://example.com`

## Overviews
```
project/ $ python3 project.py
+-+-+-+-+ +-+-+-+-+-+-+-+-+-+
|C|S|5|0| |@|a|s|r|a|j|a|l|a|l|i|
+-+-+-+-+ +-+-+-+-+-+-+-+-+-+
+-+-+-+-+-+ +-+-+-+-+-+-+-+
|F|i|n|a|l| |P|r|o|j|e|c|t|
+-+-+-+-+-+ +-+-+-+-+-+-+-+

python ./project.py
python ./project.py -u <url>
python ./project.py --url <url>

URL:
```

```
project/ $ python3 ./project.py --url https://cs50.harvard.edu/course
+-+-+-+-+ +-+-+-+-+-+-+-+-+-+
|C|S|5|0| |@|a|s|r|a|j|a|l|a|l|i|
+-+-+-+-+ +-+-+-+-+-+-+-+-+-+
+-+-+-+-+-+ +-+-+-+-+-+-+-+
|F|i|n|a|l| |P|r|o|j|e|c|t|
+-+-+-+-+-+ +-+-+-+-+-+-+-+

python ./project.py
python ./project.py -u <url>
python ./project.py --url <url>

https://cs50.harvard.edu/course Status: 404 Size: 623
# COMMENT LINES
# https://github.com/httpcats/http.cat
```

