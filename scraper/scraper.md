# 🕷️ Scraper

This project scrapes news articles from a specific website and extracts their title and body content 📰 → 🧠

## ⚙️ What it does

- Sends a request to a news listing page 🌐  
- Finds all article links on the page 🔗  
- For each link:
  - Fetches the article page 📥  
  - Extracts the title 🏷️ and body text 📄  
- Displays the scraped content directly in the notebook 💻

It’s a quick way to grab real-world text data for testing LLM prompts or training small models.

---

📍 *All logic is inside `main.ipynb`*  
💡 *Output is shown in notebook cells — not saved to disk (yet)*  
