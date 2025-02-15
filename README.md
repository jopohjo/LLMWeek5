Technical Assignment Fine-tuning using LoRA and PEFT

I run code on Kaggle and I fix some library version errors with updated pip install commands

To base model I choose TinyLlama-1.1B model and train it with dialogsum-test

Absolute percentage improvement of my fine-tuned model over ORIGINAL MODEL
rouge1: 0.90%
rouge2: 0.06%
rougeL: 4.32%
rougeLsum: 1.96%

You can find my fine-tuned model from HugginFace
https://huggingface.co/jopohjo/TinyLlama-1.1B-dialogsum-finetuned

And my source from GitHub
https://github.com/jopohjo/LLMWeek5
