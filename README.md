# AI Career Coach

This is a Python program that acts as a career coach powered by the OpenAI language model. It can assist users with resume reviews, interview preparation, career planning, job search strategies, and more.

## Getting Started

To run this program, you'll need to install the required Python libraries and have an OpenAI API key. Follow the steps below to get started:

1. Clone the repository:

2. Install the required libraries:

3. Set your OpenAI API key:

4. Load the profile data:
- Prepare a CSV file with user profile data in the format specified.
- Update the path to the CSV file in the `load_data` function.

5. Run the program:

## Functionality

- The `get_ai_response` function interacts with the OpenAI Chat Completion API to get AI-generated responses based on user input.
- The `load_data` function reads profile data from a CSV file and stores it in a list of dictionaries.
- The `ask_ai` function handles the conversation between the user and the AI career coach, using the AI model to respond appropriately based on user input and profile data.

## Limitations

- The program has a token limit for conversation history, and if exceeded, it summarizes the conversation before continuing.
