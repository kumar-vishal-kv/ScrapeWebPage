# Web Page Content Extractor

A web application for extracting and analyzing word counts and images from a given URL. The tool fetches the content from the specified URL and processes the data to return a count of all words and the URLs of all images present on the page.

## Features

- **Word Count Extraction**: Counts all the words present on the page and sorts them in descending order based on frequency.
- **Image Extraction**: Extracts all image URLs from the web page.
- **Data Caching**: Caches the fetched data for subsequent requests to improve performance.
- **User-Friendly Interface**: Easy-to-use web interface for users to input a URL and see results.

## Technologies Used

- **ASP.NET Core**: For building the backend and handling requests.
- **HtmlAgilityPack**: For parsing and extracting content from HTML.
- **Serilog**: For logging errors and events in the application.
- **C#**: Backend programming language.
- **Bootstrap**: For front-end styling.
- **GitHub**: For version control and repository management.
