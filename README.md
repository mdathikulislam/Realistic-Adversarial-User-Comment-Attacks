# Realistic Adversarial User Comment Attacks

This repository serves as the **central index** for the research project "Realistic Adversarial User Comment
Attacks".  
It provides links to all component repositories used for data preprocessing, surrogate modeling, and adversarial attack generation.

---

## Component Repositories

### Data Preparation
- **Dataset Cleaning and Splitting**  
  Repository: [fake_news_data](https://github.com/ChandlerU11/fake_news_data)  
  Description: Scripts to clean and preprocess data, creating training and testing splits for the **GossipCop** and **Politifact** datasets.

---

### Surrogate Models
- [TextCNN_Surrogate](https://github.com/ChandlerU11/TextCNN_Surrogate)  
- [dEFEND_Surrogate](https://github.com/ChandlerU11/dEFEND_Surrogate)  
- [RoBERTa_Surrogate](https://github.com/ChandlerU11/RoBERTa_Surrogate)

Each repository contains the training and evaluation pipelines for the corresponding surrogate models used to approximate the target fake news classifier.

---

### Adversarial Attack Models
- [TRL_Adversary](https://github.com/ChandlerU11/TRL_Adversary)  
  Implements a reinforcement learning–based adversarial text generation method.

- [ReST_Adversary](https://github.com/ChandlerU11/ReST_Adversary)  
  Implements a reinforcement learning–based adversarial text generation method.

- [LLM/LLM* Attacks](https://github.com/mdathikulislam/Realistic-Adversarial-User-Comment-LLMs-Attacks)  
  Implements an LLM self-reflective generative attack approach designed for iterative robustness testing.

---

## Experimental Flow

1. **Data Preparation:** Use `fake_news_data` to generate cleaned and partitioned datasets.  
2. **Model Training:** Train surrogate models using the corresponding repositories.  
3. **Adversarial Attack Generation:** Apply adversarial attack models to test robustness.  
4. **Evaluation:** Analyze model performance (accuracy, F1-score, and attack success rate).

---


