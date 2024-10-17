
This README provides instructions on how to set up and run the Streamlit Python app.

## Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

## Installation

1. Clone the repository or download the project files.

2. Navigate to the project directory in your terminal.

3. Install the required packages:

   ```
   pip install -r requirements.txt
   ```

## Environment Setup

Before running the app, you need to set up the Azure API credentials as environment variables. Use the following format:

```
AZURE_API_KEY=your_key
AZURE_ENDPOINT=your_end_point
```

You can set these environment variables in your system, or create a `.env` file in the project root directory with the above content.

## Running the App

Once you've completed the installation and environment setup, you can run the Streamlit app using the following command:

```
streamlit run curious.py
```

The app should now be running and accessible through your web browser at `http://localhost:8501`.

## Troubleshooting

If you encounter any issues:

1. Make sure all required packages are installed correctly.
2. Verify that the environment variables are set properly.
3. Check the console output for any error messages.

For further assistance, please create an issue in the project repository.
