This repo contains a notebook that can be used to run inference on a GPT-NeoX-20B model via pretrained weights downloaded from EleutherAI, using Facebook's Bitsandbytes + Huggingface's Accelerate modules to reduce the size of the model and split the inference load between GPUs in multi-GPU setups. It is designed to run locally on two RTX3090s with >=60GB of CPU RAM. It should also run on Colab Pro without modification.

This notebook demos sentiment analysis, summarization, keyword extraction, and conversational chat:

![index](https://user-images.githubusercontent.com/26489865/209953573-8f2e2ca8-9cb6-4074-961d-5755bef93703.png)
