# URL Shortener
This Flask application allows users to shorten long URLs using the pyshorteners library. It provides a simple and user-friendly interface for inputting long URLs and retrieving their shortened versions.

## Features
- URL Shortening: Input long URLs to get shortened versions using the pyshorteners library.

## Technologies Used
- Flask: A micro web framework for Python.
- HTML/CSS: For structuring and styling the web interface.
- pyshorteners: A Python library to shorten URLs.

## Installations
### Pre-requisites
- Python 3.x
- pip (Python package installer)

### Steps
Clone the repository.
```sh
git clone https://github.com/ayanabedin1105/URL-Shortener-V1.0.git
cd url-shortener
```

Create a virtual environment
```sh
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

Install the packages
```sh
pip install -r requirements.txt
```

## Running the application
Start the Flask server
```sh
python app.py
```

Open the browser
```sh
Navigate to http://127.0.0.1:5000/ to access the application.
```

## Usage
- Enter a URL starting with https:// in the input field.
- Click the "Submit" button.
- The shortened URL will be displayed below.

## Author
- Ayan Abedin (ayanabedin@gmail.com)