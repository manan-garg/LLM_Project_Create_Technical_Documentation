# LLM_Project_Create_Technical_Documentation

This Streamlit application allows you to quickly generate technical documentation for your code using the power of Gemini Pro, a generative AI model for content creation. Gemini Pro is a product of Google GenerativeAI. To try the application, visit [https://llm-project-create-technical-documentation.streamlit.app/](https://llm-project-create-technical-documentation.streamlit.app/)

## Getting Started
To use this application, follow these steps:

1. Install the dependencies, run the following command:

```pip install -r requirements.txt```

2. Run the application in your local:

```streamlit run app.py```

## Code Explanation

### Libraries Used

- Streamlit: A popular Python library for creating web applications with minimal code.
- Google GenerativeAI: This library provides access to powerful generative models, including Gemini Pro.

## App Structure
- The Streamlit app is initialized with a page title and a header.
- The sidebar allows you to input your Gemini Pro API Key securely.
- The main area includes a text area for inputting your code and a button to trigger documentation generation.

## Gemini Pro Integration
- The get_gemini_response function configures Gemini API, initializes the Gemini Pro model, and generates content based on the provided question or prompt.

## Usage
- Input your code in the text area.
- Click the "Generate Documentation" button.
- If prompted, enter your Gemini API Key in the sidebar.

## Note
- Ensure that you have an active internet connection to access the Gemini Pro API.
- Generated documentation will be displayed in the main area of the app.
- Feel free to customize the app to suit your needs or incorporate it into your workflow for efficient documentation creation.
