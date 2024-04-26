# Code Reviewer Web App

This web application is designed to assist developers in reviewing their Python code for bugs and providing suggestions for improvement. It utilizes the Streamlit framework for the user interface and integrates the OpenAI module for code reviewing.

## Features

- **Code Review:** Users can input their Python code for review.
- **Bug Detection:** The application identifies potential bugs in the code.
- **Code Correction:** Suggestions are provided for correcting the identified issues.
- **User-Friendly Interface:** Streamlit provides an intuitive and interactive interface for easy usage.

## Installation

1. Clone the repository:

    git clone https://github.com/your_username/code-reviewer.git

2. Navigate to the project directory:

    ```bash
    cd code-reviewer
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

2. Access the application through your web browser at [http://localhost:8501](http://localhost:8501).

3. Input your Python code in the provided text area.

4. Click on the "Review Code" button to initiate the code review process.

5. Review the detected bugs and suggestions provided by the application.

6. Make necessary corrections based on the suggestions provided.

7. Repeat the process until the code passes the review.
