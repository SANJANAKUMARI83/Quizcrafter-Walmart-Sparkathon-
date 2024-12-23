# Quizcrafter
QuizCrafter is an AI-driven application that generates multiple-choice questions (MCQs) from user-uploaded PDFs.

# QuizCrafter

QuizCrafter is an AI-driven application that generates multiple-choice questions (MCQs) from user-uploaded PDFs. It utilizes the Meta-Llama-3-8B model via the Groq API within a Retrieval-Augmented Generation (RAG) framework, employing ChromaDB for efficient data retrieval. The system incorporates LangChain's output parser for JSON parsing, achieving ROUGE and BERT scores of 0.47 and 0.84, respectively. The entire pipeline is deployed on Gradio, ensuring seamless usability.

## Features

- **Automated MCQ Generation**: Automatically create multiple-choice questions from uploaded PDF documents.
- **Advanced AI Integration**: Leverages the Meta-Llama-3-8B model via the Groq API for high-quality question generation.
- **Efficient Data Retrieval**: Employs ChromaDB within a Retrieval-Augmented Generation framework for effective information extraction.
- **Accurate Output Parsing**: Utilizes LangChain's output parser for precise JSON parsing, ensuring structured and accurate question formats.
- **User-Friendly Interface**: Deployed on Gradio, providing an intuitive and accessible user interface for seamless interaction.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/JAYESH1304/QuizCrafter.git
   cd QuizCrafter
   ```

2. **Set Up a Virtual Environment**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:

   ```bash
   python app.py
   ```

   Access the application at `http://localhost:7860` in your web browser.

## Usage

1. **Upload PDF**: Navigate to the application interface and upload your PDF document.
2. **Generate MCQs**: Click the 'Generate MCQs' button to initiate the question generation process.
3. **Review and Export**: Review the generated questions and export them as needed.

## Dependencies

- Python 3.8 or higher
- KerasNLP
- Gradio
- ChromaDB
- LangChain

Ensure all dependencies are installed as per the `requirements.txt` file.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.

## Acknowledgements

Special thanks to the developers of Meta-Llama-3-8B, Groq API, ChromaDB, LangChain, and Gradio for their invaluable tools and frameworks.

