[<< HOME ](https://github.com/jingwora/Generative-AI-Ultimate-Resources/blob/main/README.md)
# LLM Inference Best Practices


- [llm-inference-performance-engineering-best-practices](https://www.databricks.com/blog/llm-inference-performance-engineering-best-practices)

## Challenges in LLM Inference

## Optimizing LLM inference 

General LLM optimiztation techniques:

- Operator Fusion: Combining different adjacent operators together often results in better latency.
- Quantization: Activations and weights are compressed to use a smaller number of bits.
- Compression: Sparsity or Distillation.
- Parallelization: Tensor parallelism across multiple devices or pipeline parallelism for larger models.

Benchmarking
- Time to first token (ms)

| Model     | 1xA100-40GB       | 2xA100-40GB       | 4xA100-40GB       | 8xA100-40GB |
|-----------|-------------------|-------------------|-------------------|-------------|
| MPT-7B    | 46 (1x)           | 34 (0.73x)        | 26 (0.56x)        | -           |
| Llama2-70B| Doesn't fit       | Doesn't fit       | 154 (1x)          | 114 (0.74x) |


## Key inference metrics:

1. **Time To First Token (TTFT)**: How quickly users start seeing the model's output after entering their query. Low waiting times for a response are essential in real-time interactions, but less important in offline workloads. (milliseconds)

2. **Time Per Output Token (TPOT)**: Time to generate an output token for each user that is querying our system. (milliseconds/token)

3. **Latency**: The overall time it takes for the model to generate the full response for a user. latency = (TTFT) + (TPOT) * (the number of tokens to be generated)

4. **Throughput**: The number of output tokens per second an inference server can generate across all users and requests.

