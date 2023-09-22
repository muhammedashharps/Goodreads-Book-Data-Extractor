# Goodreads Book Data Extractor

## Overview

This project is designed to extract large datasets of book information from Goodreads based on user ratings. It includes a Python script, `main.py`, which scrapes book data from Goodreads pages and saves it to an Excel file.

## Installation

To use this project, you need to have Python installed on your system. You'll also need to install the required Python libraries. Here are the installation steps:

1. **Clone the Repository**: Clone or download this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/goodreads-book-data-extractor.git
   ```

2. **Navigate to the Project Directory**: Use the `cd` command to enter the project directory:

   ```bash
   cd goodreads-book-data-extractor
   ```

3. **Install Dependencies**: Install the required Python libraries using pip:

   ```bash
   pip install requests
   pip install bs4
   pip install openpyxl
   ```

## Usage

1. **Run the Script**:

   - Execute the `main.py` script by running the following command:

     ```bash
     python main.py
     ```

2. **Provide Input**:

   - Enter the exact link to the book list on the Goodreads website.
   - Specify the minimum rating threshold for the books you want to extract.
   - Input the total number of web pages in your book list.

3. **Data Extraction**:

   - The script will start extracting book data based on the specified criteria.
   - It will create an Excel file named `books.xlsx` in the project directory.
   - The extracted book information will be saved in this file.

4. **Excel File**:

   - You can find the extracted book data in the `books.xlsx` file in the project folder.

## Example Usage

- To scrape a list of highly rated science fiction books from Goodreads, you would provide the link to the list, set a minimum rating threshold (e.g., 4.0), and specify the total number of web pages in your list.

- The script will collect book titles, authors, and ratings meeting your criteria and save them to an Excel file for further analysis irrespective of the quantity of the dataset.

---
