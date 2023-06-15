# File Q&A with Anthropic

This project enables you to ask questions about the content of an uploaded article using the Anthropic API. It utilizes the Streamlit framework for the user interface.

## Getting Started

### Prerequisites

- Python 3.7 or higher

### Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/datamokotow/anthropic-streamlit-qna.git
   ```

2. Navigate to the project directory:

   ```shell
   cd anthropic-streamlit-qna
   ```

3. Install the required dependencies using pip:

   ```shell
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit application:

   ```shell
   streamlit run app.py
   ```

2. The application will start running locally and open in your default web browser.

3. Fill in the following inputs on the web interface:
   - **Anthropic API Key**: Enter your Anthropic API key in the provided text input.
   - **Upload an article**: Click on the "Upload an article" button and select a text file (.txt) from your local machine.
   - **Ask something about the content**: Enter your question about the content of the article in the text input.

4. If you have provided the necessary inputs (uploaded file, question, and API key), the application will display the generated answer based on the question using the Anthropic API.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- This project uses the Streamlit framework (https://www.streamlit.io/) for building the user interface.
- The Anthropic API (https://www.anthropic.com/) is used for generating answers to questions based on the uploaded article.
```

Feel free to customize the README further to fit your specific needs.
