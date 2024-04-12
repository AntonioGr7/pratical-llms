# Guide for LLM Practitioners

Welcome to the repository for LLM (Large Language Model) engineers! This collection of Jupyter Notebooks is designed to collect pratical aspects of our job. 
I will collect and add jupyter and/or script for learning and experimenting purpose. 

## Notebooks Included

| Notebook                                   | Description                                                                                                                                                                       | Url  |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|
| 1_understanding_llms_benchmarks.ipynb     | This notebook provides an explanation of the main benchmarks used in the openLLM leaderboard. It aims to help you grasp the key metrics and methodologies used in benchmarking LLMs. | [Link](#) |
| 2_quantization_base.ipynb                 | In this notebook, you'll learn how to open a Hugging Face model in 8-bit and 4-bit using the BitandBytes library. Quantization is a crucial technique for optimizing model performance and resource usage, and this notebook guides you through the process. | [Link](#) |
| 3_quantization_gptq.ipynb                 | Explore quantization in GPTQ format using the auto-gptq library with this notebook. GPTQ format is gaining popularity for its effectiveness in compressing and quantizing large models like GPT. Learn how to leverage this format for your models. | [Link](#) |
| 4_quantization_exllamav2.ipynb | How to quantize a model from HF to exllamav2 | [Link](#) |
| 5_sharding_and_offloading.ipynb | How to shard a model in multiple chunk. This allow to load it on different devices or load one at time managing memory. Learn how to offload some layer to CPU or even disk | [Link](#) |


## Additional Resources

For further resources and support, feel free to reach out to the community or refer to the following:

- [BitandBytes GitHub Repository](https://github.com/TimDettmers/bitsandbytes): Learn more about the BitandBytes library for quantization.
- [Auto-GPTQ GitHub Repository](https://github.com/AutoGPTQ/AutoGPTQ): Access the auto-gptq library for GPTQ format quantization.
- [ExLlamaV2 GitHub Repository](https://github.com/turboderp/exllamav2): Learn more about the ExLlamaV2 library for quantization and fast inference.
- [Accelerate GitHub Repository](https://github.com/huggingface/accelerate): Learn more about the Accelerate library from HF.

Happy learning and experimenting with LLMs! 🚀
