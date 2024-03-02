## Fine Tuning Llama 2 using DLora
QLoRA will use a rank of 64 with a scaling parameter of 16. We’ll load the Llama 2 model directly in 4-bit precision using the NF4 type and train it for one epoch

* Dataset:
https://huggingface.co/datasets/mlabonne/guanaco-llama2-1k
