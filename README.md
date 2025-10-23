# 1. Web Scraper – News Headlines Extractor (Python)

A simple Python script that scrapes news headlines from a given website and saves them into a text file using the **requests** and **BeautifulSoup** libraries.

---

# 2. Features

- 🌐 Fetches HTML content from a given URL  
- 🧠 Parses and extracts headlines (`<h1>`, `<h2>`, `<h3>` tags)  
- 🧹 Filters out short or irrelevant text  
- 💾 Saves clean headlines into a text file  
- ⚙️ Handles connection errors gracefully  

---

# 3. How It Works

1. The script sends a **GET request** to the target website.  
2. Parses the returned HTML content with **BeautifulSoup**.  
3. Extracts text content from headline tags (`h1`, `h2`, `h3`).  
4. Filters out very short or uninformative headlines.  
5. Saves the list of cleaned headlines to a local `.txt` file.

---

# 4. Example Usage

```bash
python scraper.py
