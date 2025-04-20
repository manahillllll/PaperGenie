# 📚 PaperGenie

**PaperGenie** is an AI-powered research assistant that helps you discover, summarize, and cite the latest papers from [arXiv](https://arxiv.org). Just enter a research topic, and PaperGenie will fetch top relevant papers, extract content from their PDFs, summarize them using a pre-trained BART model, and generate BibTeX citations — all in one click!

---

## ✨ Features

- 🔍 Search arXiv for the latest papers by topic
- 📄 Download and extract text from PDF papers
- 🧠 Generate concise summaries using Hugging Face's BART model
- 🧾 Export all results (summaries, links, citations) into a downloadable `.docx` report
- 🌐 Interactive UI powered by [Gradio](https://gradio.app/)

---

## 🛠️ Installation

```bash
git clone https://github.com/manahillllll/papergenie.git
cd papergenie
pip install -r requirements.txt

---

## ▶️ Run the App

python main.py
The app will launch in your browser at http://localhost:7860.

---

📦 Dependencies
Key Python libraries used:
transformers – for text summarization (BART model)
gradio – interactive web UI
requests – API and PDF downloads
PyMuPDF (fitz) – PDF text extraction
python-docx – Word document generation

---

📁 Output
.docx Report: Contains each paper’s title, summary, arXiv link, and BibTeX citation
Gradio Textbox: Instant summary view within the app

---

🙋‍♀️ Author
Manahil Sarwar

---

📄 License
This project is open-source and free to use under the MIT License.
