# BERT-style Models

BERT-style encoder-only models are the traditional architecture for text embeddings, producing a fixed-size vector by pooling the final hidden states of a bidirectional transformer. They are compact, fast, and well-suited for high-throughput indexing workloads where embedding quality is sufficient for the task. Models like BGE-small and all-MiniLM run efficiently on CPU or fractional GPU instances, making them the lowest-cost embedding option.

Visit the following resources to learn more:

- [@official@SentenceTransformers Documentation](https://sbert.net/)
- [@official@Using Sentence Transformers at Hugging Face](https://huggingface.co/docs/hub/sentence-transformers)
- [@article@BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
- [@article@Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks](https://arxiv.org/abs/1908.10084)