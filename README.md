# Med U Bot

Med U Bot is an AI-powered chatbot designed to provide instant and reliable medical information to users. Leveraging advanced natural language processing (NLP) technologies and machine learning algorithms, Med U Bot offers a user-friendly conversational interface for accessing accurate health-related details.

## Features

- Instant responses to medical queries
- Integration with Streamlit for a seamless user experience
- Customized chatbot framework using Langchain
- Efficient information retrieval using Faiss DB
- Trained with the llama-2-7b-chat.ggmlv3.q4_0 model
- Utilizes Hugging Face Embeddings for semantic representation
- Text splitting capabilities with Recursive Character Text Splitter
- FAISS vector store for fast and efficient similarity searches
- Conversation Buffer Memory for managing chat history and context

## Technology Stack

- **Programming Language:** Python
- **Chatbot Framework:** Langchain
- **Database:** Faiss DB
- **Machine Learning Model:** Llama-2-7b-chat.ggmlv3.q4_0
- **Embeddings:** Hugging Face Embeddings ("sentence-transformers/all-MiniLM-L6-v2")
- **Text Splitting:** Recursive Character Text Splitter
- **Vector Store:** FAISS
- **Web Application Framework:** Streamlit
- **Memory Management:** Conversation Buffer Memory

## Usage

1. Clone the repository:

```
git clone https://github.com/your-username/med-u-bot.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the application:

```
streamlit run med_u_bot.py
```

4. Access the chatbot interface in your web browser.

## Future Scope

- Expand the dataset and enhance the model's capabilities
- Integrate additional features such as voice recognition and multi-language support
- Collaborate with healthcare professionals to ensure accuracy and reliability
- Explore deployment options for broader accessibility

## Contributing

Contributions are welcome! Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README template with additional information or specific instructions for your project repository.
