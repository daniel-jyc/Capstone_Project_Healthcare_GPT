# Capstone_Project_Healthcare_GPT
This project aims to apply instruction-tuning and PEFT (Parameter-Efficient Fine-Tuning) on pre-trained Healthcare-related Large Language Models to generate medical impressions based on clinical information and radiology findings. The aim is to potentially replace some of the most labor-intensive aspects within a radiologist's workflow.

# Data Source
The data we used comes from The University of Chicago Medicine. The original dataset contains 1 million medical radiology reports including clinical information, radiology finding, and medical impression sections and is in json format.

# Computational Resources Used
- 1 x NVIDIA T4 GPU, 16GB RAM (Google Cloud- Vertex AI)

# Base Model Extended
- MedAlpaca 7b
- BioGPT
- LlaMa-2

# Model Hub
All trained and tuned LLM models are stored in my personal Huggingface storage. The link can be find here: https://huggingface.co/Danieljyc
