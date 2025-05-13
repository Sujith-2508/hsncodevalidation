# hsncodevalidation

# HSN Code Validation Assessment

## Overview
This project utilizes Google AI models to validate HSN (Harmonized System Nomenclature) codes against a predefined dataset. The application is built using Python and leverages various libraries, including `pandas` for data manipulation and Google’s AI libraries for processing.

## Features
- **HSN Code Validation**: Validates HSN codes based on specific criteria and returns descriptions.
- **Asynchronous Processing**: Utilizes `asyncio` for handling requests efficiently.
- **Excel Data Integration**: Reads HSN codes and descriptions from an Excel file.

## Prerequisites
Before running the application, ensure you have the following installed:
- Python 3.x
- pip (Python package installer)

## Installation
To install the necessary packages, run the following commands:

```bash
!pip install google-adk -q
!pip install litellm -q
