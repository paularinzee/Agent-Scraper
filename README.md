
# 🔍 Web Scraper

 A web scraper for Amazon product listings and details, built with Python and structured using a clean architecture approach.

This scraper allows you to extract key product data (like titles, prices, ratings, and more) and explore it via a user-friendly Streamlit interface.

---

## 🚀 Features

- ✅ Search for any product on Amazon by keyword
- ✅ Supports location-based scraping (e.g. us, uk, fr)
- ✅ Clean and maintainable architecture (controllers, models, enums, helpers)
- ✅ Multi-threaded for improved performance
- ✅ Streamlit UI for interactive use
- ✅ Organized codebase ready for extensions (LLM integration, analysis, etc.)

---

## ⚙️ Setup

### 🔧 Prerequisites

- Python 3.9+
- pip
- OpenAI API Key
- ScrapeOps API Key
- Anaconda

## ⚙️ Installation

```bash
# Clone the repo
git clone hhttps://github.com/paularinzee/Agent-Scraper.git
cd Agent-Scraper

# Create a conda environment
conda create --name Scraper
conda activate Scraper

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py

