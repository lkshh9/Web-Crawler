# Web Crawler for Poornima College of Engineering

## Project Description

This project is a mini web crawler designed to parse the home page of Poornima College of Engineering and generate a list of all hyperlinks found on the page. The hyperlinks are then counted based on their frequency of occurrence and sorted accordingly. This can be useful for analyzing the structure of the website and understanding which links are most commonly referenced.

## Features

- Fetches the HTML content of the specified webpage.
- Extracts all hyperlinks (`a href="..."`) from the HTML content.
- Counts the frequency of each hyperlink.
- Sorts the hyperlinks based on their frequency in descending order.
- Displays the sorted list of hyperlinks along with their frequencies.

## Dependencies

- `requests` library for making HTTP requests.
- `beautifulsoup4` library for parsing HTML content.
- `collections` library for counting frequencies (Counter).

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/lkshh9/Web-Crawler.git
    cd Web-Crawler
    ```

2. Install the required libraries:
    ```bash
    pip install requests beautifulsoup4
    ```


