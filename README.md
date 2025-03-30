# Hi there 👋



# Selected Projects

## [Text Classification using Siamese Network](https://github.com/OdedMous/Medical-Text-Classification) 
In this project, I developed an NLP classifier for detecting medical domains in texts using a Siamese Neural Network.

<img src="https://github.com/OdedMous/Medical-Transcriptions-Classification/blob/main/images/Medical_Transcription.jpg" width="500" height="250" />


## [Cross-Task Learning for Low-Resource NLP](https://github.com/OdedMous/Cross-Task-Learning-for-Low-Resource-NLP) 
NLP models require large amounts of annotated data, which are often difficult to obtain, especially in specialized fields like medicine. 💊

To address this challenge, we propose a multi-head BERT-based architecture, trained simultaneously on a 'main task' (which has limited data) and 'supporting tasks' (which have abundant data), enabling cross-task knowledge transfer.

This approach is inspired by how humans generalize knowledge across different domains. For example, learning to play the piano enhances hand-eye coordination, which can then improve performance in other activities, such as basketball.


## [Differentially Private Decoding in LLMs](https://github.com/OdedMous/DP-Decoding-in-LLM) 

Large Language Models are pre-trained on vast public data collected from the Internet, which likely contains private or sensitive information. Combined with the fact that large models tend to memorize training data, this scenario poses a potential risk of data leakage. 🔓

In this project, I reimplemented a decoding method that ensures privacy with high probability, based on the paper "Differentially Private Decoding in Large Language Models" (Majmudar et al., 2022).


<img src="https://github.com/user-attachments/assets/2a6e95dd-de21-490f-a894-08091ee3d895" width="250" height="150" />




# Blogs

## [BERxiT: Early Exiting for BERT](https://towardsdatascience.com/berxit-early-exiting-for-bert-6f76b2f561c5/) 

<img align="right" src="https://github.com/user-attachments/assets/d840ec3c-b08e-4b76-a7ee-cf93728d8f3e" width="250" height="150" />

Fast inference time is crucial for deep learning models that are deployed on resource-constrained devices, for providing real-time responses to user requests, and for cost and sustainability reasons.

In this blog I review the “early exiting” method, which improves inference time by allowing samples to exit at different depths within the network, potentially making many “easier” samples to exit early and thus avoiding unnecessary computations while still maintaining accuracy.



