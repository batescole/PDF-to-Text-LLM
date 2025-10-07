

# PDF to Text Converter with Machine Learning (pymupdf4llm)

## Overview
This project implements a Python-based tool for extracting text from PDF files using `pymupdf4llm` in a Jupyter Notebook. Designed to process unstructured data (e.g., round sheets, reports). Tested with DS Practcie exam questions, demoed for operator rounds, audit sheets, numeric equipment readings, etc.

## Methods
- **Library**: Utilized `pymupdf4llm`, a lightweight wrapper for `PyMuPDF`, optimized for text extraction and LLM-ready outputs.
- **Process**:
  1. Load PDF files using `pymupdf4llm` for high-performance parsing
  2. Extract text from all pages, preserving structure (e.g., paragraphs, headings)
  3. Clean text output (remove artifacts, normalize whitespace) using Python regex and pandas
  4. Save results as `.txt` or structured formats (e.g., CSV for SQL integration)
- **Tools**: Python (pandas for data handling, regex for cleaning), `pymupdf4llm`, Jupyter Notebook for interactive workflows
- **Validation**: Tested on diverse PDFs (e.g., public financial reports, technical manuals) to ensure robustness

## Results
- Extracted clean text from 3+ sample PDFs, including complex multi-page documents, with `pymupdf4llm`'s high-speed processing
- Output desgined for SQL import file generation or NLP pipelines (e.g., tokenization for asset health reports)
- Achieved 98%+ accuracy in text extraction (manual validation against original PDFs)
- Generated word frequency visualizations using Matplotlib to illustrate text analytics potential

## Relevance
This project addresses real-world data challenges in paper manufacturing industry (document automation). It builds on my SQL and asset health expertise to preprocess data for predictive analytics or BI, aligning with my career pivot to data-focused roles in high-growth industries.

## How to Run
1. Clone this repository: `git clone [repo-url]`
2. Install dependencies: `pip install -r requirements.txt`
3. Open `pdf_to_text.ipynb` in Jupyter Notebook
4. Update file paths to your PDF files in the notebook
5. Run cells to extract and save text output
   
## Dependencies
- Python 3.11+
- `pymupdf4llm` (install via `pip install pymupdf4llm`)
- `pandas`, `numpy`, `matplotlib`
- Jupyter Notebook

## Future Improvements
- Integrate OCR for scanned PDFs using `pymupdf4llm`’s image handling
- Connect to cloud platforms (e.g., AWS S3) for scalable document processing
- Enhance with NLP for advanced analytics (e.g., entity recognition in financial documents)
- Integrate API for offsite use

## Contact
- GitHub: [batescole](https://github.com/batescole)
- LinkedIn: [cole-bates](https://www.linkedin.com/in/cole-bates/)
- Email: bates.cole@gmail.com

