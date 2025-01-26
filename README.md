# Financial Data Extraction Tool Using OpenAI API

An advanced solution for extracting and structuring financial data from unstructured documents using the power of OpenAI's Language Learning Models (LLMs). This tool simplifies the processing of financial documents, enabling efficient and accurate information retrieval for business and personal needs.


## Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
3. [Technologies Used](#technologies-used)  
4. [Project Architecture](#project-architecture)  
5. [Setup and Installation](#setup-and-installation)  
6. [Usage](#usage)  
7. [Contributing](#contributing)  



## Overview

The **Financial Data Extraction Tool** is a robust system designed to extract critical financial information such as totals, dates, transaction details, and account data from unstructured financial documents like invoices, receipts, and reports. By utilizing OpenAI's API and innovative techniques, this tool ensures high accuracy and ease of use for users.



## Features

- **Automated Data Extraction**: Extracts key financial information with minimal manual intervention.  
- **Versatile Document Support**: Works with multiple formats, including PDF, text, and scanned images.  
- **Context-Aware Responses**: Uses LLMs to understand the document's context for accurate data extraction.  
- **Structured Outputs**: Converts unstructured data into structured formats such as JSON or CSV.  
- **User-Friendly Interface**: A simple and intuitive interface for document uploads and result visualization.  



## Technologies Used

- **Python**: Backend logic for data extraction and processing.  
- **Flask**: Framework for building the web application.  
- **OpenAI API**: Language Learning Model integration for financial document understanding.  
- **PyPDF2/PDFplumber**: PDF text extraction and parsing.  
- **Pandas**: Data structuring and manipulation.  
- **HTML/CSS/JavaScript**: Frontend design and interactivity.  



## Project Architecture

Below is the architecture of the Financial Data Extraction Tool:

```plaintext
Client (Browser)
  |
  |---> Frontend (HTML, CSS, JavaScript)
        |---> File Upload
        |---> Results Visualization
  |
  |---> Backend (Flask API)
        |---> File Handling
        |---> Extraction Pipeline
              |---> Document Parser (PyPDF2, PDFplumber)
              |---> OpenAI API Integration
              |---> Data Post-Processing
        |---> Results Formatting (JSON, CSV)
  |
  |---> Storage
        |---> Uploaded Documents
        |---> Extracted Data (Temporary Storage)
```



## Setup and Installation

### Prerequisites

Ensure the following are installed on your system:  
- Python 3.8 or later  
- pip (Python package manager)  

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/BhawnaMehbubani/Financial-Data-Extraction-Tool-Using-OpenAI-API.git
   cd Financial-Data-Extraction-Tool-Using-OpenAI-API
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables for OpenAI API key:
   ```bash
   export OPENAI_API_KEY='your_api_key_here'
   ```

5. Start the application:
   ```bash
   python app.py
   ```

6. Open your browser and navigate to `http://127.0.0.1:5000`.



## Usage

1. **Upload Financial Document**: Use the web interface to upload your financial document (e.g., PDF or text file).  
2. **Extract Data**: Initiate the extraction process, which uses LLMs for precise data understanding.  
3. **View Results**: Extracted data is displayed in a structured format (JSON or CSV).  



## Contributing

We welcome contributions! Follow these steps to contribute:  
1. Fork this repository.  
2. Create a feature branch: `git checkout -b feature-name`.  
3. Commit changes: `git commit -m "Add feature-name"`.  
4. Push to the branch: `git push origin feature-name`.  
5. Open a pull request.  

