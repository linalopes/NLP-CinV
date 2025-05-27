# NLP-CinV

This repository contains a collection of Natural Language Processing (NLP) tools and analyses focused on text processing, visualization, and topic modeling.

## Project Structure

```
.
├── data/              # Data directory
│   ├── markdown/     # Markdown files
│   ├── outputs/      # Generated outputs
│   ├── pdfs/         # input PDF files/papers
│   └── txt_clean/    # Cleaned text files
├── notebooks/         # Jupyter notebooks
│   ├── 1-conversion/  # Document conversion notebooks
│   │   ├── 1A-PDF-to-MD.ipynb
│   │   ├── 1B-Zotero-to-MD.ipynb
│   │   └── 1C-MD-to-TXT.ipynb
│   ├── 2-classic-NLP/ # Classic NLP analysis notebooks
│   │   └── 2A-NLP-Classic.ipynb
│   └── 3-RAG/        # RAG implementation notebooks
│       ├── 3A-local-RAG.ipynb
│       ├── 3B-local-RAG-gradio.ipynb
│       └── 3B-extract-with-ollama.ipynb
└── scripts/          # Utility scripts
```

## Features

- **Text Processing**: Includes preprocessing, tokenization, and lemmatization
- **Visualization**:
  - Word clouds
  - PCA (Principal Component Analysis) visualizations
  - Topic distribution plots
- **Document Conversion**:
  - PDF to Markdown conversion
  - Zotero to Markdown conversion
- **Advanced NLP**:
  - Topic modeling
  - Graph-based RAG (Retrieval-Augmented Generation)

## Requirements

The project uses Python with the following key dependencies:
- pandas
- nltk
- scikit-learn
- matplotlib
- Other NLP-related libraries

## Usage

1. **Data Preparation**:
   - Place your input files in the `input/` directory
   - Configure settings in `settings.yaml`

2. **Analysis**:
   - Run the notebooks in the following order:
     1. `2A-NLP-Classic.ipynb` for basic NLP analysis
     2. `2B-graphRAG.ipynb` for advanced graph-based analysis

3. **Document Conversion**:
   - Use `ZoteroToMD.ipynb` for Zotero export conversion
   - Use `PDF to MD.ipynb` for PDF to Markdown conversion

## Output

The analysis generates various visualizations:
- Word clouds (`cloudWord*.png`)
- PCA visualizations (`PCA*.png`)
- Topic distribution plots (`topicDistribution.png`)

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under the MIT License.
