# FastAPI URL Shortener
 This is a simple URL shortener built with FastAPI as a homework project.

## Features
-Stores data in a dictionary
-Main page with a form to submit URLs
-Endpoint to handle form submissions and generate short URLs
-Endpoint to redirect short URLs to the original links
## Installation
Clone the repository:
  ```bash
  git clone https://github.com/OleksiiUzu/fast-api-homework-19-url-shortener.git
  cd fast-api-homework-19-url-shortener
  ```
Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
Run the application:
  ```bash
  uvicorn main:app --reload
  ```
## Usage
Open http://127.0.0.1:8000/ in your browser to access the form.
Submit a long URL to get a shortened version.
Use the generated short URL to be redirected to the original link.
