# Guide for LLM Practitioners

Welcome to the repository for LLM (Large Language Model) engineers! This collection of Jupyter Notebooks is designed to collect pratical aspects of our job. 
I will collect and add jupyter and/or script for learning and experimenting purpose. 

## Notebooks Included

| Notebook                                   | Description                                                                                                                                                                       | Url  |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|
| 1_understanding_llms_benchmarks.ipynb     | This notebook provides an explanation of the main benchmarks used in the openLLM leaderboard. It aims to help you grasp the key metrics and methodologies used in benchmarking LLMs. | [Link](https://github.com/AntonioGr7/pratical-llms/blob/main/1_understanding_llms_benchmarks.ipynb) |
| 2_quantization_base.ipynb                 | In this notebook, you'll learn how to open a Hugging Face model in 8-bit and 4-bit using the BitandBytes library. Quantization is a crucial technique for optimizing model performance and resource usage, and this notebook guides you through the process. | [Link](https://github.com/AntonioGr7/pratical-llms/blob/main/2_quantization_base.ipynb) |
| 3_quantization_gptq.ipynb                 | Explore quantization in GPTQ format using the auto-gptq library with this notebook. GPTQ format is gaining popularity for its effectiveness in compressing and quantizing large models like GPT. Learn how to leverage this format for your models. | [Link](https://github.com/AntonioGr7/pratical-llms/blob/main/3_quantization_gptq.ipynb) |
| 4_quantization_exllamav2.ipynb | How to quantize a model from HF to exllamav2 | [Link](https://github.com/AntonioGr7/pratical-llms/blob/main/4_quantization_exllamav2.ipynb) |
| 5_sharding_and_offloading.ipynb | How to shard a model in multiple chunk. This allow to load it on different devices or load one at time managing memory. Learn how to offload some layer to CPU or even disk | [Link](https://github.com/AntonioGr7/pratical-llms/blob/main/5_sharding_and_offloading.ipynb) |
| 6_gguf_quantization_and_inference.ipynb | Quantize a model into GGUF using the llama.cpp library. Inferencing on OpenAI-compatible server. | [Link](https://github.com/AntonioGr7/pratical-llms/blob/main/6_gguf_quantization_and_inference.ipynb) |
| 7_gguf_split_and_load.ipynb | Split a GGUF Quantized model in multiple parts, making it easily sharable | [Link](https://github.com/AntonioGr7/pratical-llms/blob/main/7_gguf_split_and_load.ipynb) |
| 8_hqq_quantization.ipynb | Explore quantization using Half-Quadratic Quantization (HQQ) | [Link](https://github.com/AntonioGr7/pratical-llms/blob/main/8_hqq_quantization.ipynb) |


## References

For further resources and support, feel free to reach out to the community or refer to the following:

- [BitandBytes GitHub Repository](https://github.com/TimDettmers/bitsandbytes): Learn more about the BitandBytes library for quantization.
- [Auto-GPTQ GitHub Repository](https://github.com/AutoGPTQ/AutoGPTQ): Access the auto-gptq library for GPTQ format quantization.
- [ExLlamaV2 GitHub Repository](https://github.com/turboderp/exllamav2): Learn more about the ExLlamaV2 library for quantization and fast inference.
- [Accelerate GitHub Repository](https://github.com/huggingface/accelerate): Learn more about the Accelerate library from HF.
- [llama.cpp Github Repository](https://github.com/ggerganov/llama.cpp): Learn more about the llama.cpp library.
- [HQQ Github Repository](https://github.com/mobiusml/hqq): Learn more about the HQQ library.

## Additional Resources

- [Which GGUF is right for me?](https://gist.github.com/Artefact2/b5f810600771265fc1e39442288e8ec9): Useful reference on GGUF and guide on how to choose the right quantization for your scenario.
- [Interesting reddit thread on GGUF](https://www.reddit.com/r/LocalLLaMA/comments/1ba55rj/overview_of_gguf_quantization_methods/): Useful reference on GGUF.
- [Half-Quadratic Quantization of Large Machine Learning Models](https://mobiusml.github.io/hqq_blog/): HQQ Blog post
- [GPTQ vs AWS vs EXL2 vs llamacpp](https://oobabooga.github.io/blog/posts/gptq-awq-exl2-llamacpp/): Quantization method performance (Memory, Speed and VRAM) comparison

Happy learning and experimenting with LLMs! 🚀
