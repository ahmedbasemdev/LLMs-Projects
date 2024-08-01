## Fine Tuning Llama 2 using Lora
fine tunning large language model "llama 2" using PEFT and LORA for text summarization in CNN Daily Mail dataset

### LORA
LoRA decomposes a weight matrix into two smaller weight matrices, as illustrated below, to approximate full supervised fine-tuning in a more parameter-efficient manner.
![LORA](https://lightningaidev.wpengine.com/wp-content/uploads/2023/10/lora-expimage7.png)
### Dlora
QLoRA, short for quantized LoRA, is a technique that further reduces memory usage during finetuning. During backpropagation, QLoRA quantizes the pre-trained weights to 4-bit precision and uses paged optimizers to handle memory spikes.

* Dataset:
https://huggingface.co/datasets/cnn_dailymail


