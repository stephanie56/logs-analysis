# Logs Analysis

An internal reporting tool that will use information from a newspaper site database to discover what kind of articles the site's readers like. This reporting tool is a Python program using the `psycopg2` module to connect to the database.

The database contains newspaper articles, as well as the web server log for the site. The log has a database row for each time a reader loaded a web page. Using that information, the tool will answer questions about the site's user activity.

This tool will run from the command line. It won't take any input from the user. Instead, it will connect to the  database, use SQL queries to analyze the log data, and print out the answers to some questions.