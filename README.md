# TinyLlama QLoRA Fine-Tuning

Fine-tunes `TinyLlama/TinyLlama-1.1B-Chat-v1.0` with QLoRA on `mlabonne/guanaco-llama2-1k`, using Hugging Face Transformers, TRL `SFTTrainer`, PEFT LoRA adapters, and bitsandbytes 4-bit quantization.

## References

- Hugging Face Transformers bitsandbytes quantization docs: https://huggingface.co/docs/transformers/quantization/bitsandbytes  
- Hugging Face TRL SFTTrainer docs: https://huggingface.co/docs/trl/sft_trainer  
- Hugging Face PEFT LoRA docs: https://huggingface.co/docs/peft/package_reference/lora  
- TinyLlama model card: https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0  

## Project Structure

```text
.
├── train.py
├── inference.py
├── requirements.txt
├── results/
└── TinyLlama-1.1B-chat-qlora-finetune/
