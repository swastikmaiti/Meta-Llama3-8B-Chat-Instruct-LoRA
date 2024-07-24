# Meta-Llama3-8B-Chat-Instruct-LoRA
PEFT (LoRA) with Meta-Llama3-8B-Chat-Instruct

# Description

In this work we have implemented the concept of Quantization and Parameter Efficient Fine Tuning (PEFT) on Llama3-8B-Instruct. 
Quantization and PEFT are the major tools that support large scale adoption of LLM. Quantization offers the benifit of fitting a 
Memory Intensive Model into smaller spaces while preserving accuracy. PEFT allows us to fine tune Very Large Models even with 
limited resources. Without PEFT it would be impossible for most of us to fine-tune LLM. There are several existing approach to both 
Quantization and PEFT. Here we limit to application to GPTQ quantization and LoRA PEFT.



<img src="https://github.com/swastikmaiti/Meta-Llama3-8B-Chat-Instruct-LoRA/blob/d7d0f143c9b50aad0a6bef0cedbb79c3abe4983a/Lllam3-8B-Instruct-PEFT.png">


# File Structure

- quantizing-finetuning-meta-llama-8B-instruct.ipynb:- Finetuning code
- inference.ipynb:- Performing sanity check on finetuned model.

# TOOLS
- ***Qunatization:*** BitsNBytes 4bit
- ***PEFT:*** QLoRA
- ***Training:*** HuggingFace Accelerate with Training Loop

# Models and Datasets
- ***Pre-Trained Model:*** Llama-3-8b-Instruct
- ***Dataset:*** xlam-function-calling-60k


# Hugging Face

The Model is hosted on Hugging Face Repository. Refer to the Model Card for Training and uasage details.

- [Quantized Model](https://huggingface.co/SwastikM/Meta-Llama-3-8B-Instruct_bitsandbytes_4bit) @HuggingFace
- [LoRA Adapter](https://huggingface.co/SwastikM/Meta-Llama3-8B-Chat-Instruct-LoRA) @HuggingFace

#
### If you find the repo helpful, please drop a ⭐

