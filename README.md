# I-3

# ChatGPT API Interaction

A Python-based interface for interacting with ChatGPT's API, including conversation management, response streaming, and failure case testing.

## Features

- **API Interaction**
  - Single-prompt queries
  - Continuous conversation mode
  - Response streaming
  - System message customization
  - Temperature/token controls

- **Failure Testing Module**
  - Bias detection prompts
  - Hallucination triggers
  - Context limitation tests
  - Automated reporting

## Installation

1. **Requirements**
   - Python 3.7+
   - OpenAI API key

2. **Setup**
pip install openai python-dotenv
text

3. **Configuration**
Create `.env` file:
OPENAI_API_KEY=your-api-key-here
text

## Usage

### Basic API Interaction
from chatgpt_api import ChatGPTClient
client = ChatGPTClient()
Single prompt
response = client.ask("enter prompt")
print(response)
