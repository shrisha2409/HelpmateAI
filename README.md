# Mr.HelpMate AI: Generative Search System for Life Insurance Policy

## Overview
Mr. HelpMate AI, a cutting-edge retrieval-augmented generative (RAG) search system. It leverages document embedding, advanced search, and generative capabilities to provide concise and accurate answers to life insurance policy queries, ensuring high-quality, context-aware responses

## Features
- **Embedding Layer**: Processes and embeds the policy document into numerical vectors.
- **Search Layer**: Retrieves and reranks relevant document chunks using vector databases.
- **Generation Layer**: Produces well-structured answers using a language model.

## Project Structure
```
├── data/
│   └── LifePolicy.pdf        # Input PDF file of the life insurance policy
├── src/
│   ├── embedding_layer.py    # Code for embedding layer
│   ├── search_layer.py       # Code for search layer
│   └── generation_layer.py   # Code for generation layer
├── notebooks/
│   └── HelpMateAI.ipynb      # Jupyter notebook implementation
├── results/
│   └── screenshots/          # Output screenshots for queries
└── README.md                 # Project documentation
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shrish2409/HelpmateAI.git
   cd HelpmateAI
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   **Dependencies**:
   - PyPDF2
   - sentence-transformers
   - chromadb
   - faiss-cpu
   - transformers

## Usage
### Running the Project
1. **Prepare Data**:
   - Place the insurance policy document (PDF format) in the `data/` folder.
2. **Run the Jupyter Notebook**:
   - Navigate to the `notebooks/` directory and open `HelpMateAI.ipynb`.
   - Follow the cells to process the document, perform search, and generate responses.

### Example Queries
- "What are the eligibility criteria for member life insurance?"
- "What benefits are provided under accidental death and dismemberment?"
- "Define a 'Qualifying Event' as per the policy."

## Results
The system was tested with various queries and evaluated for:
- Relevance of retrieved chunks.
- Coherence and accuracy of generated answers.

Output screenshots can be found in the `results/screenshots/` directory.

## Challenges
- Extracting clean text from PDF documents.
- Fine-tuning chunking strategies to balance coherence and retrieval accuracy.
- Ensuring high-quality generative outputs through prompt engineering.

## Lessons Learned
- Preprocessing plays a crucial role in embedding quality.
- Combining retrieval and generation enhances answer relevance.
- Efficient database indexing ensures scalability for large corpora.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
Feel free to contact me!
- **Email**: shrisha2409@gmail.com
- **GitHub**: [shrisha2409](https://github.com/shrisha2409)
