This neox-20b repo contains a notebook that can be used to run inference on a GPT-NeoX-20B model with pretrained weights from EleutherAI, using Facebook's Bitsandbytes + Huggingface's Accelerate modules to reduce the size of the model and split the inference load between GPUs. It is designed to run locally on two RTX3090 GPUs with NVLink and >90GB of CPU RAM, but can be modified for bigger setups. It can also run on Colab Pro with a slightly longer inference time.
