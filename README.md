# About 

Hi there ! 👋

I like to explore the past to shape a smarter future.

# Selected Projects

## [Clinical Notes Classification using Siamese Network](https://github.com/OdedMous/Medical-Text-Classification) 
<img align="right" src="https://github.com/OdedMous/Medical-Transcriptions-Classification/blob/main/images/Medical_Transcription.jpg" width="250" height="150" />

In this project, I developed an NLP classifier for predicting medical domains in texts using a Siamese Neural Network.

The approach involves training a simple classifier with a smart representation for each text. This representation is a vector that captures the distance to text prototypes. The distance measure is learned using a dual network, consisting of a PubMedBERT model. 


## [Cross-Task Learning for Low-Resource NLP](https://github.com/OdedMous/Cross-Task-Learning-for-Low-Resource-NLP) 

<img align="right"  src="https://github.com/NivAm12/Enhancing-By-Subtasks-Components/assets/68702877/d672ae7a-e7ee-4443-88d7-3b8481e225ad" width="270" height="200" />


NLP models require large amounts of annotated data, which are often difficult to obtain, especially in specialized fields like medicine. 💊

To address this challenge, we propose a multi-head BERT-based architecture, trained simultaneously on a 'main task' (which has limited data) and 'supporting tasks' (which have abundant data), enabling cross-task knowledge transfer.

This approach is inspired by how humans generalize knowledge across different domains. For example, learning to play the piano enhances hand-eye coordination, which can then improve performance in other activities, such as basketball.


## [Differentially Private Decoding in LLMs](https://github.com/OdedMous/DP-Decoding-in-LLM) 


<img align="right"  src="https://github.com/user-attachments/assets/b3feb560-a025-4344-82d6-39c79814e5b8" width="250" height="200" />



Large Language Models are pre-trained on vast public data collected from the Internet, which likely contains private or sensitive information. Combined with the fact that large models tend to memorize training data, this scenario poses a potential risk of data leakage. 🔓

In this project, I reimplemented a decoding method that ensures privacy with high probability, based on the paper "Differentially Private Decoding in Large Language Models" (Majmudar et al., 2022), and experimented on GPT-2 and ViLT (Vision-and-Language Transformer) models. 

## [RL-based Agent for Sepsis Management](https://github.com/OdedMous/Sepsis-RL/tree/main) 

<img align="right"  src="https://github.com/user-attachments/assets/3cc5d42c-d0a9-4bb3-b058-3d4fbf09f74f" width="250" height="200" />

Sepsis is a life-threatening medical condition that can lead to organ failure and death without timely treatment in the Intensive Care Unit (ICU). Managing septic patients involves the administration of several medications, but there is no universal treatment policy due to patient variability and the complexity of the disease.

In this project, I developed a Reinforcement Learning (RL)-based agent that adjusts medication doses based on real-time clinical information from patients.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

# Blogs

## [BERxiT: Early Exiting for BERT](https://towardsdatascience.com/berxit-early-exiting-for-bert-6f76b2f561c5/) 

<img align="right" src="https://github.com/user-attachments/assets/d840ec3c-b08e-4b76-a7ee-cf93728d8f3e" width="250" height="200" />

Fast inference time is crucial for deep learning models that are deployed on resource-constrained devices, for providing real-time responses to user requests, and for cost and sustainability reasons. 🌿

In this blog I review the “early exiting” method, which improves inference time by allowing samples to exit at different depths within the network, potentially making many “easier” samples to exit early and thus avoiding unnecessary computations while still maintaining accuracy.



