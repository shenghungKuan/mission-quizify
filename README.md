# Quizzify

## Overview

The Quizzify is a web-based application designed to create and manage quizzes the generated from the uploaded PDF file. It allows users to navigate through questions, select answers, review their choices, and show the explanation for the correct answer. This application is built using Python and integrates with Streamlit for the frontend, providing an interactive and user-friendly interface.

## Features

- **Customized questions generation**: Generating customized questions based on the uploaded PDF file.  
- **Quiz cards**: Users can move between questions, choose an option and see the explanation right after.
- **Multiple Choice Questions**: Each question comes with multiple choice answers, enhancing the quiz experience.
- **Interactive UI**: Offers an engaging user interface where users can select answers and submit their responses.

## Installation

To set up the Quiz Manager Project on your local machine, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/shenghungKuan/mission-quizify.git
   ```
2. Navigate to the project directory:
   ```
   cd mission-quizzify
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Navigate to the desire task in tasks (task numbers indicate versions 10 - latest):
    ```
    cd tasks
    cd task_{the task number}
    ```
4. Run the Streamlit application:
   ```
   streamlit run task_{the task number}.py
   ```

## Usage

After launching the application, you will be presented with a quiz interface. Navigate through the questions using the provided controls, select your answers, and submit them to see your results.  

## License

Distributed under the MIT License. See `LICENSE` for more information.
