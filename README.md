# Branding Assistant

Branding Assistant is a Streamlit web app that helps you generate creative brand names, catchy slogans, and AI-generated logos for your business ideas using OpenAI's GPT and DALL·E models.

## Features

- Generate creative brand names for your business idea
- Create catchy slogans for your selected brand name
- Generate a logo using AI (DALL·E)

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/branding-assistant.git
   cd branding-assistant
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

   If `requirements.txt` is missing, install manually:

   ```bash
   pip install streamlit openai python-dotenv
   ```

4. **Set up your `.env` file:**
   Create a file named `.env` in the project root with the following content:

   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

   **Never share or commit your API key!**

5. **Run the app:**
   ```bash
   streamlit run app.py
   ```

## Usage

- Enter your business idea and click "Generate Branding Names".
- Select a brand name to generate slogans.
- Optionally, generate a logo for your selected brand name.

## Security

- Your `.env` file is included in `.gitignore` and will not be uploaded to GitHub.
- **Never share your API keys publicly.**

## License

MIT License
