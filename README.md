# Tiny GPT2 like transformer
A tiny GPT2 like Decoder-only transformer implemented with 16M parameters and 8k vocabulary size. Training was done on the [tinystories-gpt4-clean](https://huggingface.co/datasets/karpathy/tinystories-gpt4-clean) dataset, a final loss of ~1.7 was achieved after 1.5 hours of training on a RTX 4060.

Next step: Implementing the transformer without the MLP, as outlined in [paper](https://arxiv.org/abs/2607.18363) and comparing the performance.
