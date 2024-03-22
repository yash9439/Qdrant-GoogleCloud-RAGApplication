# RAG-Qdrant-GCloud: Building Enterprise Retrieval-Augmented Generation Systems

This repository provides a practical guide and implementation for building scalable Retrieval-Augmented Generation (RAG) systems using Qdrant as the retrieval engine and deploying the system on Google Cloud. RAG systems combine the capabilities of retrieval and generation models to produce high-quality, relevant text tailored to specific queries, making them valuable tools for enterprises to extract insights from large volumes of unstructured data.

## Features

- **High Performance**: Qdrant is optimized for fast vector similarity search, enabling rapid retrieval of relevant documents from large datasets.
- **Scalability**: Qdrant can handle massive datasets and high query volumes, making it suitable for enterprise-scale applications with growing data and user demands.
- **Cloud Integration**: Seamless integration with Google Cloud services, such as Cloud Run and Cloud Storage, simplifies deployment and data management.
- **Cost-Effective**: Qdrant's efficient storage and retrieval mechanisms help reduce infrastructure costs, making it an economical choice for enterprises.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Google Cloud account
- OpenAI API key (for language model integration)

### Installation

1. Clone the repository:

```
git clone https://github.com/your-username/rag-qdrant-gcloud.git
```

2. Install the required Python packages:

```
pip install -r requirements.txt
```

### Usage

1. Set up a Qdrant cluster on Google Cloud using the Qdrant Cloud service.
2. Prepare your data by extracting text from documents (e.g., PDFs) and generating embeddings using FastEmbed.
3. Start the Qdrant client and create a new collection with the appropriate vector parameters.
4. Upload the generated embeddings and associated metadata to the Qdrant cluster.
5. Generate text with a language model (e.g., GPT-4, Gemini Ultra) by passing the retrieved documents as context.

Refer to the [documentation](docs/README.md) for detailed instructions and code examples.

## Contributing

Contributions are welcome! 

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [Qdrant](https://qdrant.tech/) for providing the high-performance vector database.
- [FastEmbed](https://github.com/61repositories/FastEmbed) for efficient text embedding generation.
- [OpenAI](https://openai.com/) for their language model API.
