# prakash# Flask Docker App

A simple Flask application running in a Docker container.

## Features

- Lightweight Flask web application
- Dockerized for easy deployment

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flask-docker-app.git
   cd flask-docker-app

#### 2. `app/app.py`

```python
from flask import Flask

app = Flask(__name__)

@app.route('/')
def hello():
    return "Hello, Docker!"

if __name__ == '__main__':
    app.run(host='0.0.0.0', port=5000)
