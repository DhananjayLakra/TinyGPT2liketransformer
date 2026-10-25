# Tiny GPT2 like transformer
A tiny GPT2 like Decoder-only transformer

I implemented a tiny GPT 2 like transformer with 13M parameters and 50K vocabulary size. Training was done using RTX 4060, was able to bring loss down to 2.3 with ~1 hour of training.
Next step: Implementing the transformer without the MLP, as outlined in the Simple Attention network (SAN) paper by Cactus Compute and comparing the performance.
