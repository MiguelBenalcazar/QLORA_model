### INSTALL REQUIREMENTS

!pip install -q -U bitsandbytes

!pip install -q -U git+https://github.com/huggingface/transformers.git

!pip install -q -U git+https://github.com/huggingface/peft.git

!pip install -q -U git+https://github.com/huggingface/accelerate.git

!pip install -q datasets

!pip install -q -U wandb ml-collections


https://github.com/artidoro/qlora

Quantization: If you trained your model with a quantized base, it's generally recommended to maintain that during inference to ensure performance and memory efficiency 25.

Performance: Some users have noted that loading models with specific configurations (like double quantization) may lead to slower inference times; thus, experimenting with settings may be beneficial 56.

PEFT Integration: The integration of Parameter-Efficient Fine-Tuning (PEFT) methods allows for seamless loading and merging of adapter weights, enhancing flexibility in model usage 25.
