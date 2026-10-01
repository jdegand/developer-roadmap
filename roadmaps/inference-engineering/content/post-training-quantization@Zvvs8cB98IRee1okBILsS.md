# Post-Training Quantization

Post-training quantization converts finished model weights to lower precision after training is complete, using a small calibration dataset to compute per-layer scale factors that minimize the gap between quantized and original outputs. It is the standard approach for most deployments since it requires no retraining and can be applied to any existing model. The leading tool is NVIDIA ModelOpt, which exports quantized models in formats compatible with all major inference engines.

Visit the following resources to learn more:

- [@opensource@AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration](https://github.com/mit-han-lab/llm-awq)
- [@opensource@bitsandbytes](https://github.com/TimDettmers/bitsandbytes)
- [@opensource@SmoothQuant](https://github.com/mit-han-lab/smoothquant)
- [@article@GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers](https://arxiv.org/abs/2210.17323)
- [@article@LLM.int8(): 8-bit Matrix Multiplication for Transformers at Scale](https://arxiv.org/abs/2208.07339)
- [@article@SparseGPT: Massive Language Models Can Be Accurately Pruned in One-Shot](https://arxiv.org/abs/2301.00774)