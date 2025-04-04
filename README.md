# pinecone-semantic-indexing-embedding-search-engine
# Quora Semantic Search with Sentence Transformers and Pinecone

This project demonstrates how to build a **semantic search engine** using sentence embeddings, vector similarity, and Pinecone. It leverages the **Quora Questions dataset** and the `all-MiniLM-L6-v2` model from the `sentence-transformers` library.

> 💡 Originally created as part of a course project at Cairo University.

---

## 📌 Features

- 🔍 **Semantic Search** over real-world question pairs
- 🤖 Uses `all-MiniLM-L6-v2` from `sentence-transformers`
- 📦 Stores and queries vectors using **Pinecone**
- 🧠 Encodes questions into dense vector representations
- 🧪 Example queries included for interactive exploration

---

## 🛠️ Technologies Used

| Tool / Library       | Purpose                              |
|----------------------|--------------------------------------|
| `datasets`           | Load Quora question pairs            |
| `sentence-transformers` | Generate sentence embeddings       |
| `Pinecone`           | Vector database and similarity search |
| `torch`, `tqdm`      | Model execution and progress display |

---

## 📈 Example Use Cases
- Smart Q&A systems
- Duplicate question detection
- Content recommendation
- FAQ search
