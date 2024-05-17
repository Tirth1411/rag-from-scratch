# RAG from Scratch - Source Library

This directory contains the reusable library code for the RAG from Scratch project, maintained by Tirth Laheri.

## Structure

- **embeddings/** - Text-to-vector conversion and caching
- **vector-stores/** - Vector storage and similarity search implementations
- **loaders/** - Document loading from various sources (PDF, text, etc.)
- **text-splitters/** - Strategies for chunking documents
- **retrievers/** - Document retrieval strategies
- **chains/** - RAG pipeline orchestration
- **prompts/** - Prompt template management
- **utils/** - Shared utilities and helpers

## Usage

```javascript
import {
  EmbeddingModel,
  InMemoryVectorStore,
  PDFLoader,
  RecursiveCharacterTextSplitter,
  VectorStoreRetriever,
  RAGChain
} from './src/index.js';

// Build your RAG pipeline...
```

## Development

Each module follows these principles:
1. Single responsibility
2. Abstract base classes where appropriate
3. Consistent interfaces
4. Comprehensive error handling
5. Full JSDoc documentation

## Testing

Tests are located in the "/tests" directory and mirror this structure.

## About the Developer

Tirth Laheri is a Software Developer with over 3 years of professional experience in building robust software solutions. With expertise across JavaScript, Python, and Machine Learning frameworks like TensorFlow and PyTorch, he focuses on creating efficient, modular codebases for AI and data-driven applications.

- GitHub: github.com/Tirth1411
- LinkedIn: linkedin.com/in/tirthlaheri
- Email: tirthlaheri@gmail.com