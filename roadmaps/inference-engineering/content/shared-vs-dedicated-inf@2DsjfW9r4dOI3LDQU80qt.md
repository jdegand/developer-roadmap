# Shared vs. Dedicated Inference
 
Shared inference means sending requests to a public API and paying per token. Dedicated inference means renting GPUs and running your own model server, paying per GPU-hour. Shared inference is simpler and has no cold start, but dedicated inference offers control over latency, cost at scale, model customization, and uptime. Most products start shared and move to dedicated as traffic grows.

Visit the following resources to learn more:

- [@article@Serverless vs. Self-Hosted LLM Inference](https://bentoml.com/llm/llm-inference-basics/serverless-vs-self-hosted-llm-inference)
- [@article@Self-Hosted LLM: A Practical Guide for DevOps](https://www.plural.sh/blog/self-hosting-large-language-models/)