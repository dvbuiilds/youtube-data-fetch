# Fetching comments from YT videos using YouTube Data API
This project contains python script for fetching video comments typically for 4 famous Indian Journalists from their prime time show videos.
The purpose of this project is to create comments dataset for NLP and ML projects.

## Installation
If you look into the file, the first cell includes all python packages necessary for the project. To install them, you simply need to run the cell.

## Credentials
Log onto Google Developer Console and open YouTube Data API. After completing all formalities, create an app and generate your API Key. You can simultaneously create multiple apps and generate individual keys for each of them. On the developer console, you can also have a look on the daily API calls you have made and the daily limits. Save the key in a json file named `credentials.json`.

## Enjoy fetching data from the API
The script also involves handling the complex json response received from the YT server, structurizing the data into a table and storing the table in CSV file. 
