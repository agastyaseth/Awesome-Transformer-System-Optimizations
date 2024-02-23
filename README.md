# Awesome Hardware-Aware Transformer Inferencing Optimizations

A curated list of resources and research papers focused on optimizing transformer model inferencing with a keen eye on hardware efficiency. This compilation is part of the ML Accelerator Design course (CSE598) at Arizona State University, dedicated to exploring, understanding, and innovating on the intersection of hardware capabilities and transformer model efficiencies.

## Contents

- [Surveys](https://chat.openai.com/c/53c5dfd2-7093-4d68-b963-6496a4bd782c#surveys)
- [Pruning and Compression](https://chat.openai.com/c/53c5dfd2-7093-4d68-b963-6496a4bd782c#pruning-and-compression)
- [Speculative Decoding](https://chat.openai.com/c/53c5dfd2-7093-4d68-b963-6496a4bd782c#speculative-decoding)
- [Parallelization and Decoding Techniques](https://chat.openai.com/c/53c5dfd2-7093-4d68-b963-6496a4bd782c#parallelization-and-decoding-techniques)
- [Exploring Sparsity](https://chat.openai.com/c/53c5dfd2-7093-4d68-b963-6496a4bd782c#exploring-sparsity)
- [I/O Awareness and Dataflow Optimization](https://chat.openai.com/c/53c5dfd2-7093-4d68-b963-6496a4bd782c#io-awareness-and-dataflow-optimization)
- [Memory Management](https://chat.openai.com/c/53c5dfd2-7093-4d68-b963-6496a4bd782c#memory-management)
- [Hardware-aware Inference Efficiency](https://chat.openai.com/c/53c5dfd2-7093-4d68-b963-6496a4bd782c#hardware-aware-inference-efficiency)
- [Additional Resources](https://chat.openai.com/c/53c5dfd2-7093-4d68-b963-6496a4bd782c#additional-resources)

## Surveys

- **Towards Efficient Generative Large Language Model Serving: A Survey from Algorithms to Systems** - [Read](https://arxiv.org/abs/2312.15234)
- **A Survey on Model Compression and Acceleration for Pretrained Language Models** - [Read](https://ojs.aaai.org/index.php/AAAI/article/view/26255)
- **Faster and Lighter LLMs: A Survey on Current Challenges and Way Forward** - [Read](https://arxiv.org/abs/2402.01799)
- **Unlocking Efficiency in Large Language Model Inference: A Comprehensive Survey of Speculative Decoding** - [Read](https://arxiv.org/abs/2401.07851)
- **Hardware-friendly Compression and Hardware Acceleration for Transformer: A Survey** - [Read](https://www.aimspress.com/aimspress-data/era/2022/10/PDF/era-30-10-192.pdf)

## Pruning and Compression

- **LLM-Pruner: On the Structural Pruning of Large Language Models** - [Read](https://arxiv.org/abs/2305.11627)
- **LLMLingua: Compressing Prompts for Accelerated Inference of Large Language Models** - [Read](https://arxiv.org/abs/2310.05736)
- **AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration** - [Read](https://arxiv.org/abs/2306.00978)
- **SpQR: A Sparse-Quantized Representation for Near-Lossless LLM Weight Compression** - [Read](https://arxiv.org/abs/2306.03078)
- **Efficient LLM Inference on CPUs** - [Read](https://arxiv.org/abs/2311.00502)

## Speculative Decoding

- **SpecInfer: Accelerating Generative Large Language Model Serving with Tree-based Speculative Inference and Verification** - [Read](https://arxiv.org/abs/2305.09781)
- **Accelerating LLM Inference with Staged Speculative Decoding** - [Read](https://arxiv.org/abs/2308.04623)
- **Draft & Verify: Lossless Large Language Model Acceleration via Self-Speculative Decoding** - [Read](https://arxiv.org/abs/2309.08168)

## Parallelization and Decoding Techniques

- **Inference with Reference: Lossless Acceleration of Large Language Models** - [Read](https://arxiv.org/abs/2304.04487)
- **Medusa: Simple LLM Inference Acceleration Framework with Multiple Decoding Heads** - [Read](https://arxiv.org/abs/2401.10774)
- **Accelerating LLaMA Inference by Enabling Intermediate Layer Decoding via Instruction Tuning with LITE** - [Read](https://arxiv.org/abs/2310.18581v2)

## Exploring Sparsity

- **Sparse Fine-tuning for Inference Acceleration of Large Language Models** - [Read](https://arxiv.org/pdf/2310.06927.pdf)
- **Flash-LLM: Enabling Cost-Effective and Highly-Efficient Large Generative Model Inference with Unstructured Sparsity** - [Read](https://arxiv.org/abs/2309.10285)
- **ReLU Strikes Back: Exploiting Activation Sparsity in Large Language Models** - [Read](https://arxiv.org/abs/2310.04564)

## I/O Awareness and Dataflow Optimization

- **FlashAttention and FlashAttention-2** - [Read 1](https://arxiv.org/abs/2205.14135), [Read 2](https://arxiv.org/abs/2307.08691)
- **Blockwise Parallel Transformer for Large Context Models** - [Read](https://arxiv.org/abs/2305.19370)
- **FlashDecoding++: Faster Large Language Model Inference on GPUs** - [Read](https://arxiv.org/pdf/2311.01282.pdf)

## Memory Management

- **Efficient Memory Management for Large Language Model Serving with PagedAttention** - [Read](https://arxiv.org/abs/2309.06180)

## Hardware-aware Inference Efficiency

- **DeepSpeed-Inference** - [Read](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10046087)
- **Efficiently Scaling Transformer Inference** - [Read](https://proceedings.mlsys.org/paper_files/paper/2023/hash/523f87e9d08e6071a3bbd150e6da40fb-Abstract-mlsys2023.html)

## Additional Resources

- **LLM in a Flash: Efficient Large Language Model Inference with Limited Memory** - [Read](https://arxiv.org/abs/2312.11514)
- **A Practical Survey on Faster and Lighter Transformers** - [Read](https://arxiv.org/pdf/2103.14636.pdf)
- **Beyond the Limits: A Survey of Techniques to Extend the Context Length in Large Language Models** - [Read](https://arxiv.org/pdf/2402.02244.pdf)