# gpt-code-reviewer

gpt-code-reviewer is a Python script that automates the code review process using OpenAI's GPT-3.5 language model. It interacts with users through a command line interface and GitHub API to retrieve code for review.

## Requirements

This script requires the following Python packages:

- os
- openai
- rich
- requests

It also requires access to a GitHub account and an OpenAI API key.

## Usage

You need to set two environment variables `GITHUB_TOKEN` and `OPENAI_API_KEY`.

Clone the repository and navigate to its directory in your terminal. Then, run the following command:

`cp config.yaml.example config.yaml`

Edit `config.yaml` to suit your needs.

Run this command to start the application.

`python3 main.py`

The script will prompt you to select a repository and pull request to review. You will then be prompted to enter 'r' to review the code, 'q' to quit, 'h' for help, and 'n' to review a different pull request.

The language model will provide suggestions and feedback based on your input, and you can continue to review the code until you are finished.

## License

This script is licensed under the MIT License. See the LICENSE file for details.
