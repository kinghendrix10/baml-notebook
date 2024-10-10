# BAML Notebook

## Overview

This project is a Jupyter notebook that demonstrates how to use the BAML (Boundary AI Machine Learning) library to extract resume information using various clients. The notebook includes code for installing dependencies, mounting Google Drive, initializing a BAML project, and extracting resume information.


## Running the Notebook

1. Open the Jupyter notebook `BAMLDev.ipynb` in Jupyter or Google Colab.

2. Follow the instructions in the notebook to run the cells sequentially.

## Usage Examples

### Extracting Resume Information

The notebook provides examples of how to extract resume information using different clients. Here are some examples:

## Configuration Details

### API Keys

To use the BAML clients, you need to set the appropriate API keys. The notebook uses the `python-dotenv` library to load environment variables from a `.env` file. Make sure to create a `.env` file in your Google Drive or local environment with the following content:

```
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
```

## Troubleshooting and Common Issues

### Common Issues

1. **Command not found**: If you encounter a "command not found" error when running `!baml-cli init`, make sure that the BAML CLI is installed and available in your PATH.

2. **API Key Errors**: Ensure that your API keys are correctly set in the `.env` file and that the file is loaded properly.

3. **Dependency Issues**: If you encounter issues with dependencies, try reinstalling them using the `pip install` commands provided in the setup section.

For further assistance, refer to the [BAML documentation](https://docs.boundaryml.com/docs/get-started/quickstart/python).
