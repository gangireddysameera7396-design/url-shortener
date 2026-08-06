# URL Shortener

## Overview

URL Shortener is a Python-based web application that converts long URLs into short, easy-to-share links. The application generates a unique short code for each URL and redirects users to the original link when accessed.

## Features

* Convert long URLs into short links
* Generate unique short codes
* Redirect short URLs to original URLs
* Simple web-based interface
* Fast URL processing
* Lightweight Flask application

## Technologies Used

* Python 3
* Flask Framework
* HTML
* Web Routing

## Project Structure

```text id="m7q2kx"
url-shortener/
│── app.py
│── requirements.txt
│── README.md
```

## Requirements

Install the required package:

```bash id="p5n8vq"
pip install flask
```

Or add Flask to:

```text id="x9m4kp"
requirements.txt

flask
```

## Getting Started

### Prerequisites

* Python 3.x installed on your system

Check Python version:

```bash id="k3v7mx"
python --version
```

### Installation

1. Clone the repository:

```bash id="n8q2pz"
git clone https://github.com/your-username/url-shortener.git
```

2. Navigate to the project directory:

```bash id="q6m3vx"
cd url-shortener
```

3. Install dependencies:

```bash id="r4k9np"
pip install -r requirements.txt
```

4. Run the application:

```bash id="w7m2kx"
python app.py
```

5. Open your browser and visit:

```text id="h5n8qm"
http://127.0.0.1:5000/
```

## Usage

Example:

```text id="z3k7vp"
Enter Long URL:

https://www.example.com/my-long-web-page

Generated Short URL:

http://127.0.0.1:5000/aB91xZ
```

Opening the short URL redirects the user to the original website.

## Learning Objectives

This project demonstrates:

* Python web development
* Flask framework basics
* URL routing
* HTTP redirects
* Random string generation
* Dictionary-based data storage
* Web application structure

## Future Improvements

* Add database support using SQLite/MySQL
* Add user authentication
* Add URL expiration dates
* Add click analytics
* Add QR code generation
* Deploy the application online

## License

This project is open source and available under the MIT License.
