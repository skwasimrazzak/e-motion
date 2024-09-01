# e-motion


## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Directory Structure](#directory-structure)
4. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)

## Overview
e-motion is a project designed to analyze emotions from facial features (image data). The project includes Python scripts, HTML templates, CSS styles, and a pre-trained model to deliver accurate emotion detection.

## Features
- Emotion detection from images
- Frontend built with HTML, CSS, and JavaScript
- Backend powered by Python and a pre-trained model

## Directory Structure
```plaintext
e-motion/
│
├── .devcontainer
├── .github
├── pythonScripts/     # User-defined python package
│   ├── __init__.py
│   ├── clickPhoto2.py # Script to click photo and save
│   ├── preProcess.py  # Script to pre-process data (image file)
│   └── predict.py     # Script to analyze data using pre-trained model
├── .gitignore
├── README.md
├── app.js             # Static JavaScript file
├── index.html         # HTML template
├── main.css           # CSS file
├── model2.h5          # Pre-trained model files
├── requirements.txt   # Python dependencies
└── server.py          # Main server script
```

## Getting Started

### Prerequisites
- Python 3.x
- Flask

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/PALLADIUM26/e-motion.git
   ```
2. Navigate to the project directory:
   ```bash
   cd e-motion
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
- Navigate to `http://localhost:5000` in your browser to start using e-motion.
- Run the server on terminal:
   ```bash
   python server.py
   ```

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.
