#      Smart Review System



## Introduction
Smart Review System is a web application designed to provide information about available courses and their reviews.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

## Features
- **Course Availability**: Browse and search for available courses.
- **Review System**: Users can read and write reviews for courses.
- **Sentiment Analysis**: Reviews are analyzed using Azure Text Analysis to provide sentiment insights.
- **Image to Text**: Capture and convert text from images using Azure Vision Services.
- **Text to Speech**: Convert text content into speech using Azure Speech Services.
- **Built-in Browser**: Integrated browser functionality using Bing Search API.+
- **Flask Framework**: The application is built using the Python Flask framework for web development.

## Installation
To install and run the Smart Review System locally, follow these steps:

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/smart-review-system.git 
cd smart-review-system
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
### 2. Set up a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate  
```

### 3.Install dependencies:
```bash
pip install -r requirements.txt
```

### 4. Set up environment variables:
##### Create a .env file in the project root and add your Azure API keys and other configuration settings:
```bash
AZURE_TEXT_ANALYSIS_KEY=your_key_here
AZURE_VISION_KEY=your_key_here
AZURE_SPEECH_KEY=your_key_here
BING_SEARCH_API_KEY=your_key_here
```
### 5. Run the application:
```bash
flask run
```
## Usage
* Browse Courses: Navigate to the course catalog to browse available courses.
* Read Reviews: View reviews and sentiment analysis for each course.
* Write Reviews: Submit your own reviews for courses.
* Extract Text from Images: Upload images to extract text content.
* Text to Speech: Convert text reviews to speech.
## Dependencies
* Python 3.x
* Flask
* Azure Cognitive Services (Text Analysis, Vision, Speech)
* Bing Search API

## Configuration
The application requires the following environment variables to be set:

* AZURE_TEXT_ANALYSIS_KEY
* AZURE_VISION_KEY
* AZURE_SPEECH_KEY
* BING_SEARCH_API_KEY

## Documentation

* Detailed documentation is available in the docs folder, covering API usage, architecture, and more.

## Contributors
* Sandeep Gudisa - Project Lead
* Sandeep Gudisa - Developer
* Sandeep Gudisa - Designer

