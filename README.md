WriteWise


---

# Customer Service Model Response Checker

This Flask application serves as a customer service model response checker, leveraging OpenAI's GPT-4 Turbo model and TruLens Evals for analytical and fine-tuning capabilities.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Frontend Setup](#frontend-setup)
4. [Backend Setup](#backend-setup)
5. [Demo](#demo)
6. [Contributing](#contributing)
7. [License](#license)

## Installation

To run this application locally, you'll need to follow these steps:

### Step 1: Install Python and Flask

1. **Install Python**: Ensure Python 3.6 or later is installed on your system. You can download it from [python.org](https://www.python.org/).

2. **Install Flask**: Flask can be installed using pip, Python's package installer.

   ```bash
   pip install Flask
   ```

### Step 2: Create a Virtual Environment

1. **Create a Virtual Environment**: Navigate to your project directory and run:

   ```bash
  pyenv install 3.9.7
    ```

2. **Activate the Virtual Environment**:

   - On Windows: `venv\Scripts\activate`
   - On Unix or MacOS: `source venv/bin/activate`

### Step 3: Install Dependencies

```bash
pip install openai trulens_eval chromadb
```

## Usage

### Frontend Setup

1. **Set Up the `templates` Directory**: Create a `templates` directory in the root of your project.

2. **Craft the `index.html` File**: Inside the `templates` directory, create an HTML file named `index.html` with the provided HTML code.

### Backend Setup

1. **Create the Flask Application**: Define your Flask application in a Python script (e.g., `app.py`) using the provided Python code.

2. **Run the Flask Application**: Start the Flask development server by running the command `flask run`.

## Demo

Once the application is running locally, you can interact with it by:

- Entering information in the text area and input field.
- Selecting the feedback options as per your requirement.
- Clicking the "Process Query" button to see how the application processes the input and returns results.

## Contributing

Contributions are welcome! If you'd like to enhance this application or fix any issues, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

