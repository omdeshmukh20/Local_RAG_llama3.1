Chat with Webpage using Local Llama3 and RAG

This project allows users to chat with any webpage using local Llama3 and Retrieval-Augmented Generation (RAG). The system extracts webpage content, splits it into chunks, generates embeddings, stores them in a FAISS vector database, retrieves relevant information based on user queries, and generates responses using the Llama3 model.

🚀 Features

Load Webpage Data: Extracts text from a given URL.

Text Chunking: Splits the text into manageable pieces for efficient retrieval.

Embeddings & Vector Storage: Converts text into vectors and stores them in FAISS.

Retrieval-Augmented Generation (RAG): Searches for relevant content before responding.

Local Llama3 Model: Generates human-like responses.

Streamlit UI: Interactive web interface for querying webpage content.

📂 Project Structure

Local_Llama3_RAG/

│── app.py               # Main entry point (Run this file)

│── loader.py            # Loads webpage content

│── splitter.py          # Splits text into chunks

│── embedding.py         # Converts text into vectors

│── model.py             # Llama3 model for response generation

│── retriever.py         # Retrieves relevant info from the database

│── requirements.txt     # Required Python libraries

│── README.md            # Project documentation

🛠 Installation

1️⃣ Clone the Repository

git clone https://github.com/yourusername/Local_Llama3_RAG.git
cd Local_Llama3_RAG

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Application

streamlit run app.py

📝 How It Works

User Inputs a Webpage URL → The system extracts webpage text.

Text is Chunked → The extracted content is split into small parts for better searchability.

Embeddings are Generated → The text chunks are converted into vector embeddings using Llama3.

Vectors are Stored in FAISS → The FAISS vector database helps in quick retrieval of relevant text.

User Asks a Question → The system searches for the most relevant content.

Llama3 Generates a Response → The model generates an answer based on the retrieved context.

📌 Example Usage

Enter a webpage URL.

Click "Load Webpage".

Enter a question related to the webpage content.

Get a response powered by local Llama3 + RAG.

📜 License

This project is licensed under the MIT License.

✨ Contributions

Contributions are welcome! Feel free to submit issues or pull requests.

📞 Contact

For any queries, reach out via GitHub or email at -omdeshukh2026@gmail.com.
