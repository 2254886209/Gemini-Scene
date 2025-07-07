# 🚨 Enhancing Dangerous Scene Classification with Multimodal LLMs & Attention Mechanisms

Zhang, D., Xie, T., Wu, S., Duan, S., & Wang, L. (2025). Enhancing Dangerous Scene Classification with
Multimodal LLMs and Attention Mechanisms. The Visual Computer
---

📜  Abstract
---
In the realm of computer vision, the classification of dangerous scenes in crowded environments, such as the rising popularity of tourist destinations, poses significant challenges. Traditional safety monitoring methods heavily rely on manual supervision, which is inadequate for real-time risk identification to ensure the safety of life and property. This is particularly challenging in crowded environments, where transitioning from manual monitoring to human-machine collaboration is imperative. The advent of large language models (LLMs) provides an opportunity to enhance safety systems. With their vast parameter scale, these models improve the precision and generalization ability of conventional vision models. With the introduction of DeepSeek, the high-cost barriers to using large model have been significantly lowered. This study introduces Gemini-Scene, a novel multimodal framework leveraging large language models (LLMs) and attention mechanisms to classify dangerous scenes accurately. We construct a comprehensive dataset focused on hazardous scenarios and develop the multimodal network Gemini-Scene. By integrating image embeddings, textual descriptions, and scene probabilities from pre-trained models such as CLIP and BERT, our framework aligns multimodal features through a self-attention mechanism. The model achieves a hazard scene classification accuracy of 97.5%, significantly outperforming existing deep learning methods with accuracies below 77.5%. Experimental results demonstrate that Gemini-Scene achieves a classification accuracy of 97.5%, significantly outperforming existing methods with accuracies below 77.5%. This framework offers an advanced solution for next-generation safety monitoring in high-risk, densely populated areas. The code is available at https://github.com/2254886209/Gemini-Scene.

## 📦 Quick Start

```bash
git clone https://github.com/YourUsername/Gemini-Scene.git
cd Gemini-Scene

🖥 Experimental Environment

This code is intended to run on Google Colab for maximum convenience and rapid debugging.
The open-source release includes:

```Main classification model

```All ablation-study variants

```Dataset construction scripts

```Raw dataset archive

📊 Experimental Environment

We’ve _added detailed explanations to every section of the notebooks_ so you can follow our workflow step by step.
Simply run each cell from top to bottom in the following order:

```Dataset setup & preprocessing

```Open and execute dataset_method.ipynb to build and preprocess the dataset.

```Model training & evaluation

```Open and execute Main_Model+Ablation_model.ipynb to train the main model and all ablation variants.
Review inline metrics (accuracy, F1 score) and visualizations (loss curves, attention maps).

#By following this sequence, you will fully reproduce the experiments and results reported in our paper! 
