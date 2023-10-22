[<< HOME ](https://github.com/jingwora/Generative-AI-Ultimate-Resources/blob/main/README.md)
# LLM Inference Best Practices

## Challenges in LLM Inference

## Optimizing LLM inference 

General LLM optimiztation techniques:

- Operator Fusion: Combining different adjacent operators together often results in better latency.
- Quantization: Activations and weights are compressed to use a smaller number of bits.
- Compression: Sparsity or Distillation.
- Parallelization: Tensor parallelism across multiple devices or pipeline parallelism for larger models.


## Key inference metrics:

1. **Time To First Token (TTFT)**: How quickly users start seeing the model's output after entering their query. Low waiting times for a response are essential in real-time interactions, but less important in offline workloads. (milliseconds)

2. **Time Per Output Token (TPOT)**: Time to generate an output token for each user that is querying our system. (milliseconds/token)

3. **Latency**: The overall time it takes for the model to generate the full response for a user. latency = (TTFT) + (TPOT) * (the number of tokens to be generated)

4. **Throughput**: The number of output tokens per second an inference server can generate across all users and requests.

