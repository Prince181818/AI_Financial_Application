# AI Financial Assistant 

An AI-powered financial assistant built with Python, OpenAI API, and Gradio. It helps users understand how their monthly income can be allocated toward spending, investments, taxes, and savings.

##  Features

- **AI-Powered Assistant:** Uses an OpenAI language model to understand and respond to user messages.
- **Income Calculation:** Calculates suggested allocations based on the user's monthly salary.
- **Financial Breakdown:** Provides a breakdown of:
  - 50% – Spending
  - 20% – Investments
  - 10% – Taxes
  - 20% – Savings
- **Function Calling:** Uses OpenAI tool calling to execute the income calculation function.
- **Interactive Chat Interface:** Built using Gradio for easy communication with the assistant.
- **Simple Responses:** Designed to provide concise and easy-to-understand financial suggestions.

## 🛠️ Technologies Used

- Python
- OpenAI API
- Gradio
- JSON
- Function Calling (Tool Calling)

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/AI_Financial_Application.git
```

### 2. Navigate to the project directory

```bash
cd AI_Financial_Application
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install openai gradio
```

### 6. Configure your OpenAI API key

Set your API key as an environment variable:

```powershell
$env:OPENAI_API_KEY="your_api_key"
```

### 7. Run the application

```bash
python app.py
```

The Gradio interface will open in your browser.

##  How It Works

1. The user enters their monthly salary through the Gradio chat interface.
2. The OpenAI model processes the user's message.
3. If an income calculation is required, the model calls the `get_income` function.
4. The function calculates the suggested allocation for spending, investments, taxes, and savings.
5. The calculated results are returned to the AI model.
6. The assistant generates a simple response for the user.

##  Project Structure

```text
AI_Financial_Application/
│
├── app.py
├── README.md
└── .venv/
```

## ⚠️ Disclaimer

This project is an educational demonstration of AI-powered financial assistance and OpenAI function calling.

The allocation percentages are fixed illustrative assumptions, not personalized financial recommendations. Tax calculations do not represent actual tax liability.

## 👨‍💻 Author

**Prince Timilsena**

GitHub: [Prince181818](https://github.com/Prince181818)

LinkedIn: [Prince Timilsena](https://www.linkedin.com/in/prince-timilsena-329197356/)