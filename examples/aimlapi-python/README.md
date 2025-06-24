# AI/ML API with E2B Code Interpreter

This example demonstrates how to run the [AI/ML API](https://aimlapi.com/app/?utm_source=e2b&utm_medium=github&utm_campaign=integration) with the [E2B Code Interpreter SDK](https://github.com/e2b-dev/code-interpreter).
The script sends a prompt to an AI/ML API model and executes the returned Python code in a secure E2B sandbox.

## Prerequisites
- Python 3.11+
- `AIML_API_KEY` and `E2B_API_KEY` environment variables

## Run the example
Install dependencies and execute the script:
```bash
pip install openai e2b-code-interpreter python-dotenv
python main.py
```
