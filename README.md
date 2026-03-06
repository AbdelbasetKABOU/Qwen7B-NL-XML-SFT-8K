# Qwen7B NL→XML SFT (8K)

The repository contains experiments on fine-tuning Qwen2.5-7B-Instruct to translate AMI deployement descriptions in natural language ***(NL)*** into structured ***XML*** configurations, using Supervised Fine-Tuning ***(SFT)*** with LoRA and an ***8K*** context window _(8192 tokens)_. 

The experiments are conducted on Colab using A100 GPU. The pipeline follows the same dataset format and workflow used in the companion project but adapted for 8K context training and evaluation. 

For a lighter version of the pipeline using 4K context and local GPU, see the related repository: _[Qwen-NL-XML-SFT](https://github.com/AbdelbasetKABOU/Qwen-NL-XML-SFT)_.