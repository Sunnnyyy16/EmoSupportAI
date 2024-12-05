![header](https://capsule-render.vercel.app/api?type=venom&color=0:A8D08D,100:EAF7E0&height=300&section=header&text=SupportlyChat%20&fontSize=90)

# SupportlyChat
This is our code implementation of the paper "Enhancing Emotions in a Positive Way: LLM-Based AI Using CBT for Emotional Support"
![js](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## Environment
We experiment codes in Colab environment.
Python: 3.10

## Key Features

* Model Architecture: Built on the Llama 3.2-1B, an optimized auto-regressive transformer language model. \
* Fine-Tuning: Leveraged the MentalWell dataset and applied Low-Rank Adaptation (LoRA) to enhance performance. \
* Purpose: Refined to generate empathetic and supportive responses tailored to users' daily life narratives and emotional states.

## Data
For this study, we construct custom dataset, [MentalWell.csv]()
This dataset is a combination of [Mental Health Datasets]() and [HappyDB]()

## Code Guideline
Our proposed method consists of two parts: 
1) Fine-tuned Llama 
2) Visualization

To demonstrate our chatbot(SupportlyChat), we constructed three type prototype. You can access directly to the code below links.
1) [MH-Llama]() : fine-tuned with Mental Health Datasets
2) MH-Llama Visual: [MH-Llama]() and [emotion visualization]()  
3) SupportlyChat: [fine-tuned Llama with MentalWell dataset]() and [emotion visualization]()


For more details, please refer to the paper.

<div align="center">
  <img src="https://github.com/user-attachments/assets/193f51c1-4206-4499-95d5-768633cfa861" alt="Centered Image" width="350">
</div>




