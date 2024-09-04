## Goal: follow and recreate what Andrej Karpathy has done in his tutorial Building Makemore series (Neural Networks: Zero to Hero). https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ

## Here are short descriptions for the contents in each folder: 

## MakeMore_DL_Review

These five tutorials serve as warm-ups or reviews of deep learning concepts, building neural networks from scratch to generate new names.

## Tiny_GPT_From_Scratch

This section recreates a small and manageable LLM using minimal PyTorch, named `Tiny_GPT_dev_(8.9M bits).ipynb`.

Re-implement GPT2 (124 M parameter). 【partically followed】

## Tokenization

This section includes code for the byte-level Byte Pair Encoding (BPE) algorithm commonly used in LLM tokenization. The BPE algorithm is "byte-level" because it operates on UTF-8 encoded strings.

This algorithm was popularized for LLMs by the GPT-2 paper and the associated GPT-2 code release from OpenAI. The original reference for using BPE in NLP applications is cited as Sennrich et al. (2015). Today, all modern LLMs (e.g., GPT, Llama, Mistral) use this algorithm to train their tokenizers.

### For completeness, this repository also includes implementations of Bigram, Tiny GPT, MakeMore, Tokenization, and GPT2 as Python scripts in corresponding folders, closely mirroring the versions from Andrej’s repository. My current focus is on notebooks; I may come back and rewrite Python scripts later. 

#### His original repos: 
##### DL Zero to Hero: https://github.com/karpathy/nn-zero-to-hero
##### GPT2: https://github.com/karpathy/nanoGPT
##### Tokenization: https://github.com/karpathy/minbpe

