# Flask Meme Website

This is a simple Flask application that fetches memes using an API and displays them on a website. It's a fun project created for learning the basics of Flask and integrating external APIs.

## Getting Started

To get started with the project, follow the instructions below:

### Prerequisites

- Python 3.x installed on your system
- pip package manager

### Installation

1. Clone the repository to your local machine or download the source code as a ZIP file.
2. Open a terminal or command prompt and navigate to the project directory.
3. Install the required Python packages by running the following command:
```
pip install -r requirements.txt
```


### Usage

1. In a terminal or command prompt, navigate to the project directory.
2. Run the following command to start the Flask application:
```
python meme_flask.py
```
3. Open a web browser and visit `http://localhost:8080` to view the meme website.
4. The webpage will display a random meme along with the subreddit it came from.
5. The page will automatically refresh every 30 seconds to fetch and display a new meme.

### Customize

- If you want to use a specific meme subreddit, you can uncomment the lines in `meme_flask.py` that specify the subreddit and modify them accordingly. For example:
```
sr = "/wholesomememes"
url = "https://meme-api.herokuapp.com/gimme" + sr
```
- Feel free to modify the HTML template (meme_index.html) to customize the look and feel of the website according to your preferences.

### Contributing

This project was created for learning purposes, but contributions are welcome. If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

### Acknowledgements

1. The project uses the Flask framework for building the web application. More information about Flask can be found at Flask [Documentation](https://flask.palletsprojects.com).
2. The memes are fetched from the [meme-api.com](https://meme-api.com) API.