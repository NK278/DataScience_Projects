# DataScience_Projects

#  Project1: Flask Web Scraping Application

This Flask application performs web scraping on Flipkart to retrieve product reviews based on user input. It utilizes the Flask web framework, Beautiful Soup for web scraping, and requests for making HTTP requests.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- Flask
- Flask-CORS
- requests
- BeautifulSoup4

You can install them using the following command:

```bash
pip install -r requirements.txt
```

### Running the Application

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repo
   ```

3. Run the Flask application:

   ```bash
   python your_app_file.py
   ```

   Replace `your_app_file.py` with the name of your Flask application file.

4. Open your web browser and go to [http://localhost:5000/](http://localhost:5000/) to access the application.

## Usage

1. Access the homepage by visiting [http://localhost:5000/](http://localhost:5000/).

2. Enter the product or content you want to search for in the provided input field.

3. Click the "Search" button.

4. The application will fetch reviews from Flipkart based on the provided input and display the results.

## Features

- **Homepage:** Provides a simple user interface with an input field to enter the search query.

- **Review Page:** Retrieves reviews from Flipkart for the specified product and displays them on the results page.

- **Logging:** The application logs relevant information, including any errors encountered during the scraping process, into a log file (`scrapper.log`).

## Issues and Contributions

Feel free to open issues or contribute to the project by submitting pull requests. Your feedback and contributions are welcome!

---



---

# Project2: Flask Image Scraping Application

This Flask application performs image scraping from Google based on a user's search query. It utilizes the Flask web framework, Beautiful Soup for web scraping, requests for making HTTP requests, and MongoDB for storing image data.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- Flask
- Flask-CORS
- requests
- BeautifulSoup4
- pymongo

You can install them using the following command:

```bash
pip install -r requirements.txt
```

### MongoDB Configuration

1. Create a MongoDB Atlas account (https://www.mongodb.com/cloud/atlas).
2. Set up a cluster and obtain the connection string.

### Running the Application

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repo
   ```

3. Run the Flask application:

   ```bash
   python your_app_file.py
   ```

   Replace `your_app_file.py` with the name of your Flask application file.

4. Open your web browser and go to [http://localhost:8000/](http://localhost:8000/) to access the application.

## Usage

1. Access the homepage by visiting [http://localhost:8000/](http://localhost:8000/).

2. Enter the search query for images in the provided input field.

3. Click the "Search" button.

4. The application will fetch images from Google based on the provided query and store them in the `images/` directory. Image data will also be stored in MongoDB.

## Features

- **Homepage:** Provides a simple user interface with an input field to enter the search query.

- **Image Scraping:** Fetches images from Google based on the provided query and saves them in the `images/` directory.

- **MongoDB Integration:** Stores image data, including index and image content, in MongoDB.

- **Logging:** The application logs relevant information, including any errors encountered during the scraping process, into a log file (`scrapper.log`).

## MongoDB Configuration

Set up your MongoDB Atlas connection by replacing the MongoDB connection string in the `app.py` file with your own connection string.

## Issues and Contributions

Feel free to open issues or contribute to the project by submitting pull requests. Your feedback and contributions are welcome!

---



---

# Project 3:  Flask YouTube Data Scraper

This Flask application uses the YouTube API to fetch data from a specific YouTube channel, stores it in a CSV file, and then displays the data on a webpage. The application provides a simple interface to showcase YouTube video details.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- Flask
- google-api-python-client
- google-auth
- google-auth-oauthlib
- google-auth-httplib2

You can install them using the following command:

```bash
pip install -r requirements.txt
```

### YouTube API Key Setup

1. Create a project on the Google Cloud Console (https://console.developers.google.com/).
2. Enable the YouTube Data API v3 for your project.
3. Create API credentials (API key) for your project.

### Running the Application

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repo
   ```

3. Run the Flask application:

   ```bash
   python your_app_file.py
   ```

   Replace `your_app_file.py` with the name of your Flask application file.

4. Open your web browser and go to [http://localhost:5000/](http://localhost:5000/) to access the application.

## Usage

1. The application fetches YouTube data (title, published date, thumbnails, and views) from a specific channel using the YouTube API.

2. The data is stored in a CSV file named `youtube_data.csv`.

3. The application then reads the CSV file and displays the YouTube data on the homepage.

## Features

- **YouTube Data Fetching:** Fetches data from a specific YouTube channel using the YouTube API.

- **CSV Storage:** Stores the fetched data in a CSV file for future reference.

- **Webpage Display:** Displays the YouTube data on a simple webpage.

- **Error Logging:** Logs any errors encountered during the process in the `scrapper.log` file.

## Issues and Contributions

Feel free to open issues or contribute to the project by submitting pull requests. Your feedback and contributions are welcome!

---
