# scraperai
## 📦 Installation Guide

To run this project smoothly, follow the steps below to install all necessary dependencies:

### ✅ 1. Uninstall Conflicting Versions

```bash
pip uninstall -y youtube-search-python httpx
```

### ✅ 2. Install Compatible Versions

```bash
pip install youtube-search-python==1.6.4 httpx==0.23.0
```

### 🎭 3. Playwright for Web Scraping

```bash
pip install playwright nest_asyncio
playwright install  # Only needed once to download browser binaries
```

### 🧠 4. Embeddings + Vector Search

```bash
pip install -q faiss-cpu sentence-transformers
```

### 🔥 5. Transformers + LLM

```bash
pip install -q transformers accelerate bitsandbytes
pip install -U transformers accelerate
```

---

You’re now ready to run the full project including:

* Web scraping from Bing & websites
* YouTube search & Hacker News
* Chunking, vector indexing, and LLM summarization

Happy building! 💻🚀
