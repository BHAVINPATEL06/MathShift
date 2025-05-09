# Math Solver

A powerful AI-powered math problem solver built with Streamlit and LangChain, leveraging Groq's Llama 3.3 70B model for advanced mathematical reasoning and problem-solving capabilities.

## Features

- 🤖 AI-powered math problem solving using Groq's Llama 3.3 70B model
- 🔢 Built-in calculator for mathematical computations
- 📚 Wikipedia integration for additional context and information
- 💡 Detailed step-by-step explanations for solutions
- 🎯 Support for various types of mathematical problems
- 💬 Interactive chat interface for natural problem input

## Prerequisites

- Python 3.x
- Groq API key
- Required Python packages (listed in requirements.txt)

## Installation

1. Clone the repository:
```bash
mkdir MathShift
cd MathShift
```

Clone the repo

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project root and add your Groq API key:
```
GROQ_API_KEY=your_api_key_here
```

## Usage

1. Start the Streamlit application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the provided local URL (typically http://localhost:8501)

3. Enter your math question in the text area and click "find my answer" to get the solution

## How It Works

The application uses a combination of:
- LangChain for orchestrating the AI workflow
- Groq's Llama 3.3 70B model for advanced reasoning
- Wikipedia API for additional context
- LLMMathChain for mathematical computations
- Streamlit for the user interface

## Project Structure

```
math-solver/
├── app.py              # Main application file
├── requirements.txt    # Python dependencies
├── .env               # Environment variables
└── README.md          # Project documentation
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
