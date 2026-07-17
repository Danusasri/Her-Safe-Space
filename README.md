# Her-Safe-Space
Developed a semantic image retrieval system using OpenCLIP embeddings and FAISS vector indexing, enabling sub-second similarity search across a dataset of 5,000+ images. Expanded dataset coverage by 40% through automated web scraping.
🚀 Project Overview
This tool allows you to:

Scrape images from websites
Generate AI-based embeddings for images
Store embeddings in a vector index
Perform similarity search (reverse image search)
Query using REST APIs
Interact via a React frontend interface
🏗 System Architecture
1️⃣ Image Scraping (Ingestion Layer)
Scrapes images from target URLs
Downloads and stores them locally

2️⃣ Embedding Layer
Converts images into numerical vectors using pretrained AI models

3️⃣ Vector Index Layer
Stores embeddings efficiently
Enables fast nearest-neighbor search

4️⃣ Query Layer
Accepts query image
Generates embedding
Returns top-K similar images

5️⃣ Frontend Layer
React-based UI
Upload image and view similar results

📂 Project Structure
AI-Based-Image-Similarity-WEB-Scrapping-tool/
│
├── api/                # Backend API endpoints
├── ingestion/          # Web scraping logic
├── embedding/          # AI embedding generation
├── vector_index/       # Vector indexing logic
├── query/              # Similarity search module
├── services/           # Shared backend services
├── data/               # Stored images and metadata
├── frontend-react/     # React frontend application
├── tests/              # Unit and integration tests
├── requirements.txt    # Python dependencies
└── README.md
