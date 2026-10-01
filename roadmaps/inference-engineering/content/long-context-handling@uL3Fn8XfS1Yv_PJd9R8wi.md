# Long Context Handling
 
Long sequences produce KV caches large enough to strain GPU memory, slow down decode, and increase prefill time. Techniques for handling long context include FlashAttention for memory-efficient attention computation, PagedAttention for non-contiguous KV storage, chunked prefill to interleave long prefill with decode, and model-level approaches like sliding window attention that limit how many prior tokens each token attends to.

Visit the following resources to learn more:

- [@article@Ring Attention with Blockwise Transformers for Near-Infinite Context](https://arxiv.org/abs/2310.01889)
- [@article@RoFormer: Enhanced Transformer with Rotary Position Embedding](https://arxiv.org/abs/2104.09864)