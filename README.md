# my-new-project

Project connected to [GitHub](https://github.com/jashhhhhhhh).

## Day1 & Day2 notebooks (LLM Engineering)

- **day1.ipynb** – OpenAI (or Ollama) + website summarization; uses `scraper.py`.
- **day2_I.ipynb** – Ollama + Selenium-based scraping for JS-heavy sites.

### Run the code

1. **Create a virtual environment and install deps**
   ```powershell
   cd c:\Users\mjkum\projects\my-new-project
   python -m venv .venv
   .venv\Scripts\activate
   pip install -r requirements.txt
   ```

2. **Day1 (OpenAI)**  
   Copy `.env.example` to `.env`, add your `OPENAI_API_KEY`, then open `day1.ipynb`, select the `.venv` kernel, and run all cells.

3. **Day2 (Ollama)**  
   Install and start [Ollama](https://ollama.com), pull `llama3.2`, then open `day2_I.ipynb` and run. No API key needed.
