# 🔮 Project Sora – Your Personal AI Assistant  

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Async](https://img.shields.io/badge/Asyncio-Supported-brightgreen)
![LangChain](https://img.shields.io/badge/LangChain-Integrated-orange)
![Status](https://img.shields.io/badge/Status-Active-success)

> 🌟 *"A local AI-powered assistant that understands your files - like Jarvis for your documents."*

---

## 📖 About the Project

**Project Sora** is an AI-driven personal assistant designed to **index, search, and analyze your local files intelligently**. Built with scalability in mind, it uses asynchronous Python to efficiently crawl through directories and create a searchable metadata index — all locally, no data leaves your machine.

Think of it as the **foundation of a smart local AI assistant**: capable of understanding your file system, ready to be extended with natural language search, LLM integrations, and even a web interface.

This project follows **production-grade coding practices**:
- Modular design
- Async-first approach
- Clean separation of concerns
- Comprehensive logging
- Future extensibility with LangChain & OpenAI

---

## ✨ Features

- 📂 **Smart File Indexing**  
  Crawl multiple directories and build a structured index of all files with metadata (name, path, extension).

- ⚡ **Asynchronous Processing**  
  Uses `asyncio` and non-blocking I/O for high performance, even on large file systems.

- 🔍 **Fast & Flexible Search**  
  Filter files by name, type, path, or size — optimized for quick retrieval.

- 🧠 **AI-Ready Architecture**  
  Designed for seamless integration with **LangChain**, **OpenAI**, or any LLM pipeline.

- 📊 **Built-in Logging System**  
  Every operation is logged with timestamps and status levels (`INFO`, `ERROR`, etc.) for debugging and monitoring.

- 🚀 **Production-Grade Structure**  
  Modular codebase: easy to extend, test, and maintain.

---

## 🏗️ Project Architecture

## ⚙️ Tech Stack

| Category        | Technology Used                          |
|----------------|------------------------------------------|
| Language        | Python 3.10+                             |
| Async Framework | `asyncio`, `os`                          |
| File Handling   | `pathlib`, `os.walk`                     |
| Logging         | `logging` module                         |
| Future Tools    | LangChain, OpenAI API, FastAPI (planned) |

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Ayushpal2006/Project-Sora.git
cd Project-Sora
```

## 🔧 2. Create Virtual Environment

```bash
python -m venv venv
```

## 3. Activate the Virtual Environment
On Windows:
```bash
venv\Scripts\activate
```
On macOS/Linux:
```bash
source venv/bin/activate
```
## 4. Install Dependencies
```bash
pip install -r requirements.txt
```

## 5. Run the Project
```bash
python main.py
```
# 📂 Folder Structure
| Path               | Type  | Description                                      |
|--------------------|-------|--------------------------------------------------|
| `main.py`          | File  | Entry point – runs the indexing process         |
| `indexer.py`       | File  | Core logic: async file crawling & metadata extraction |
| `utils/`           | Folder| Contains utility modules                          |
| `utils/logger.py`  | File  | Centralized logging setup (file + console handlers) |
| `utils/helpers.py` | File  | Helper functions (e.g., `get_file_size`, `get_extension`) |
| `logs/`            | Folder| Stores log files (created at runtime)            |
| `logs/app.log`     | File  | Auto-generated application log file              |
| `requirements.txt` | File  | List of Python dependencies                      |
| `README.md`        | File  | Project documentation and guide                  |
| `.gitignore`       | File  | Specifies files to exclude from version control  |

## 💡 Why This Project Stands Out?

### ✅ Uses real async programming, not just sync code with async keyword
### ✅ Production-grade structure: separate modules, logging, error handling
### ✅ Scalable design — easy to plug in AI, web APIs, DBs

# 🧑‍💻 Author
### Ayush Pal

### 🔗 [GitHub: @Ayushpal2006](https://github.com/Ayushpal2006)


📜 License
MIT License Copyright (c) 2024 Ayush Pal Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

