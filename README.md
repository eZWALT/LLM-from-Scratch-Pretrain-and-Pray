# Transformer from Scratch Pretrain&Pray

## Description

> “What I cannot create, I do not understand.”  
> — Richard Feynman

**For the curious mind wondering how Transformers and LLMs work under the hood**


This repository is aimed to build a Transformer language model from scratch by training a classical OG encoder-decoder architechture, going through contextual and postional embeddings, attention layers and using Reddit Data to perform Pretraining (And praying everything is alright) on commodity hardware.

Tech stack used:
- Python 
- PyTorch

## Contents


## Install / Usage 

Firstly install the dependencies using pip, pyenv, uv, conda... Although PyENV is seriously recommended to isolate completely the python version and deps while being open-source:

```sh
pyenv virtualenv 3.12.11 llm
pyenv local llm 
pyenv activate llm
```


## Credits 

Walter J. Troiani and the original authors of Attention is all you need :)

## License

This project is licensed under the Apache 2.0 License. See the [LICENSE](./LICENSE) file for details.
