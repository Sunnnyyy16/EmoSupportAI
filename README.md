![header](https://capsule-render.vercel.app/api?type=venom&color=0:A8D08D,100:EAF7E0&height=300&section=header&text=SupportlyChat%20&fontSize=90)

# SupportlyChat
This is our code implementation of the paper "Enhancing Emotions in a Positive Way: LLM-Based AI Using CBT for Emotional Support"
![js](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## Environment
We experiment codes in Google Colab environment. We highly recommend to run the code files in Colab enviornment. \
Python: 3.10

## Key Features

* Model Architecture: Built on the Llama 3.2-1B, an optimized auto-regressive transformer language model. 
* Fine-Tuning: Leveraged the MentalWell dataset and applied Low-Rank Adaptation (LoRA) to enhance performance. 
* Purpose: Refined to generate empathetic and supportive responses tailored to users' daily life narratives and emotional states.

## Data
For this study, we construct custom dataset, [MentalWell.csv](https://github.com/Sunnnyyy16/EmoSupportAI/blob/main/MentalWell.csv). \
This dataset is a combination of [Mental Health Datasets](https://huggingface.co/datasets/nbertagnolli/counsel-chat) and [HappyDB](https://www.kaggle.com/datasets/ritresearch/happydb).

## Hugging Face link
We uploaded our Fine-tuned Llama to the Huggingface. 
* [MH-LLaMa](https://huggingface.co/dhlim55/mental_health_llama_basic)
* [SupportlyChat](https://huggingface.co/dhlim55/mental_health_happydb_llama)
* [How to install huggingface hub](https://huggingface.co/docs/huggingface_hub/ko/installation)
  
## Code Guideline
Our proposed method, SupportlyChat consists of two parts: 
1) Fine-tuned Llama with MentalWell dataset
2) Emotion Visualization

Also, to demonstrate our proposed method(SupportlyChat), we construct three prototypes. 
1) MH-Llama : fine-tuned with Mental Health Datasets
2) MH-Llama Visual: MH-Llama and emotion visualization
3) SupportlyChat: fine-tuned Llama with MentalWell dataset and emotion visualization

We offer three codes. You can access the codes directly if you click colab icons
1) Fine-tuned with Mental Health Datasets(MH-Llama): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sunnnyyy16/EmoSupportAI/blob/main/MH_LLaMa.ipynb)
2) Fine-tuned Llama with MentalWell dataset(SupportlyChat's Chat function): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sunnnyyy16/EmoSupportAI/blob/main/SupportlyChat.ipynb)
3) Emotion visualization (emotion visualization function of MH-Llama and SupportlyChat): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sunnnyyy16/EmoSupportAI/blob/sunny/user_input_visualization.ipynb)


For more details, please refer to the paper.

<div align="center">
  <img src="https://github.com/user-attachments/assets/193f51c1-4206-4499-95d5-768633cfa861" alt="Centered Image" width="350">
</div>




