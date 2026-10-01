# Containerization
 
Containerization packages an inference service and all its dependencies into a Docker image that runs consistently across environments. Inference containers include the CUDA toolkit, Python packages, the inference engine, and any system libraries like ffmpeg for audio processing. Using a pinned dependency tree prevents breaking changes from affecting running services and ensures reproducible builds.

Visit the following resources to learn more:

- [@official@Kubernetes Documentation](https://kubernetes.io/docs/home/)