
# API Data Fetching and Storing Assignment

This assignment demonstrates skills in working with the fetching and savingd data through API using Python. For this purpose, I have chosen Google Books API. The goal of the assignment is to fetch book data from the API, filter the results based on specific criteria, and save the data to a CSV file. The assignment tests skills in working with APIs, data fetching, data manipulation, and file handling in Python.

## Assignment Description

My assignment focuses on fetching book data from the Google Books API and saving it to a CSV file. The following tasks are performed:

1. Connect to the Google Books API using an API key.
2. Define the search criteria, such as the query term and desired maximum number of books.
3. Fetch the books from the API in batches, handling pagination correctly to retrieve more than 40 results.
4. Filter the fetched books to exclude duplicates based on book IDs.
5. Display each book's details before saving it to the CSV file.
6. Save the book data to a CSV file, with columns for title, authors, and year.

## Steps to Run the Assignment

1. Obtain a Google Books API key from the Google Cloud Console.
2. Install the necessary dependencies, including requests and pandas, using pip. 
3. Save the provided Python code in a Jupyter Notebook or a Python file.
4. Replace `'YOUR_API_KEY'` in the code with your actual API key.
5. Run the code, either in a Jupyter Notebook or by executing the Python file.

## Output

Running the code will fetch book data from the Google Books API, filter out duplicates, and save the data to a CSV file named 'books.csv'. The output will include the following:

- Display of each book's details (title, authors, year) before saving it to the CSV file.
- The CSV file 'books.csv' will be generated in the same directory as the code.
- The CSV file will contain the book data in a tabular format, with columns for Title, Authors, Year,	Publisher, Page Count, Average Rating, Rating Count. 

Please note that the number of books fetched and saved depends on the value of `TOTAL_BOOKS` specified in the code. The chosen value is 800, but you can modify it according to your requirements.
