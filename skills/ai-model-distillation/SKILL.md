---
name: ai-model-distillation
description: Compress large AI models into small, ultra-fast versions.
---

# AI Model Distillation

This skill enables bionicbot to take a 'Teacher' model (like Claude 3 Opus) and train a smaller 'Student' model to perform the same task with 90% accuracy at 10x the speed.

## Instructions
1. Identify the specific task and the high-performance Teacher model.
2. Generate a large synthetic dataset using the Teacher's outputs.
3. Train a smaller architecture (e.g., Llama-3-8B) on the Teacher's reasoning patterns.
4. Validate the performance and deploy as a cost-effective alternative.

## Examples
- "Distill our 'Financial Analysis' model to run on-device for mobile users."