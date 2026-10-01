# Reasoning Models
 
Reasoning models generate an intermediate thinking sequence before producing their final output, adding a third token sequence alongside the input and output. This reasoning trace increases total token count significantly and changes inference economics: TTFT is higher, total latency is longer, and output token costs dominate. Inference engineers must account for the variable and sometimes very long reasoning sequences when sizing infrastructure and setting latency budgets.

Visit the following resources to learn more:

- [@article@Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)