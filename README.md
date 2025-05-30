
# AI Knowledge Worker using Chroma

A lightweight AI-powered knowledge worker built on Chroma for efficient data storage and retrieval.

## Features

- **Semantic Vector Store**  
  Uses Chroma for fast, scalable vector indexing.  
- **Document Ingestion**  
  Supports PDF, TXT, and Markdown files.  
- **Query Interface**  
  Simple CLI for natural language queries.  
- **Extensible**  
  Easily plug in new data sources or embedding models.

## Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/Rishi-Kora/AI-Knowledge-Worker-using-Chroma.git
   cd AI-Knowledge-Worker-using-Chroma


2. Create a virtual environment

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ingest documents

   ```bash
   python ingest.py --path /path/to/docs
   ```
2. Start query session

   ```bash
   python query.py
   ```
3. Enter your questions and receive AI-generated answers based on your document corpus.

## Contributing

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m "Add YourFeature"`)
4. Push to branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

