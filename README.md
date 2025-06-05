# finetune_llama3

# LLaMA-3 Fine-Tuning with Unsloth (4-bit)
This project demonstrates how to fine-tune the LLaMA-3 8B model using 4-bit quantization via the Unsloth library. The workflow includes data preparation, model loading, training, and evaluation — all designed to be GPU-efficient, especially in Colab environments.




![image](https://github.com/user-attachments/assets/362d653b-c76e-45f2-9080-3ba92528aceb)



# Features


Uses Unsloth for efficient loading and training of LLaMA models.

Leverages 4-bit quantization for low-resource GPU usage.

Automatically installs dependencies based on GPU capability.

Supports sequence length up to 2048 tokens.

Integrates LoRA-based fine-tuning and HuggingFace Hub.
