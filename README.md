# Linguistic_Technology
LLM Multilingual comparative study on IMDB Movie reviews

Welcome to our repository! We hope you find your visit interesting 😁😁😁

This is an abstract of our work

This study evaluates the performance of Large Language Models (LLMs) for sentiment analysis across three linguistically diverse languages: English, Greek, and Ukrainian. It is the first benchmarking or this configuration and those models in 3 discreet languages. We compare a locally deployed small language model (Llama 3.2 3B) against two cloud-based models (OpenAI ChatGPT and Google Gemini) using a subset of the IMDB Movie Reviews dataset under both Zero-Shot and Few-Shot prompting. Performance is assessed with Accuracy, Precision, Recall, and F1-score. Across all languages, prompting settings, and metrics, Llama demonstrates the best overall performance (mean 88.1% across all reported metric values), consistently outperforming Gemini (73.5%) and ChatGPT (69.7%). Llama achieves particularly strong results in English and Ukrainian, where it reaches 93–96% accuracy and 92–96% F1 depending on the prompting strategy. However, Llama’s cross-lingual generalization is less stable in Greek, and Few-Shot prompting leads to a marked degradation compared to Zero-Shot (Greek Accuracy from 84.5% to 68.1%, F1 from 84.1% to 68.3%), indicating negative transfer effects when adding in-context examples. Importantly, Few-Shot prompting does not yield consistent improvements and often reduces performance for the cloud models as well. Overall, the results highlight the trade-offs between model deployment constraints and multilingual robustness, showing that a compact locally deployed model can achieve the strongest aggregate performance, while still facing challenges in stable generalization across languages and prompting regimes.

Dataset
dataset.csv contains 1001 randomly selected comments along with their groundtruth labels (positive or negative). Initial dataset link https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews


