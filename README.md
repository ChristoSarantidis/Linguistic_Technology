# Linguistic_Technology
LLM Multilingual comparative study on IMDB Movie reviews

Welcome to our repository! We hope you find your visit interesting 😁😁😁

This is an abstract of our work.

This study evaluates the performance of Large Language Models (LLMs) for sentiment analysis across three linguistically diverse languages: English, Greek, and Ukrainian. It is the first benchmarking or this configuration and those models in 3 discreet languages. We compare a locally deployed small language model (Llama 3.2 3B) against two cloud-based models (OpenAI ChatGPT and Google Gemini) using a subset of the IMDB Movie Reviews dataset under both Zero-Shot and Few-Shot prompting. Performance is assessed with Accuracy, Precision, Recall, and F1-score. Across all languages, prompting settings, and metrics, Llama demonstrates the best overall performance (mean 88.1% across all reported metric values), consistently outperforming Gemini (73.5%) and ChatGPT (69.7%). Llama achieves particularly strong results in English and Ukrainian, where it reaches 93–96% accuracy and 92–96% F1 depending on the prompting strategy. However, Llama’s cross-lingual generalization is less stable in Greek, and Few-Shot prompting leads to a marked degradation compared to Zero-Shot (Greek Accuracy from 84.5% to 68.1%, F1 from 84.1% to 68.3%), indicating negative transfer effects when adding in-context examples. Importantly, Few-Shot prompting does not yield consistent improvements and often reduces performance for the cloud models as well. Overall, the results highlight the trade-offs between model deployment constraints and multilingual robustness, showing that a compact locally deployed model can achieve the strongest aggregate performance, while still facing challenges in stable generalization across languages and prompting regimes.

The file dataset.csv contains 1001 randomly selected comments along with their groundtruth labels (positive or negative). Initial dataset link https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews.

Herein we present the radar charts of our findings.

Figure 1: English in Zero Shot configuration.
<img width="800" height="800" alt="zero_english" src="https://github.com/user-attachments/assets/b090450a-7809-48b5-87ea-50affef860f0" />


Figure 2: Greek in Zero Shot configuration.
<img width="800" height="800" alt="zero_greek" src="https://github.com/user-attachments/assets/94747b70-b38c-4f3c-951f-84ca292fb24b" />


Figure 3: Ukrainian in Zero Shot configuration.
<img width="800" height="800" alt="zero_ukrainian" src="https://github.com/user-attachments/assets/b3a28fd1-f4b9-4f34-bfcc-e8b42612081d" />


Figure 4: English in Few Shot configuration.
<img width="800" height="800" alt="few_english" src="https://github.com/user-attachments/assets/74aaaefb-adef-47d1-a787-5418eee9c696" />


Figure 5: Greek in Few Shot configuration.
<img width="800" height="800" alt="few_greek" src="https://github.com/user-attachments/assets/1d2fb807-63de-45c1-b394-c1be6454efe6" />


Figure 6: Ukrainian in Few Shot configuration.
<img width="800" height="800" alt="few_ukrainian" src="https://github.com/user-attachments/assets/f90250fb-2556-434b-8c90-9ab6ba497601" />

For anything that you would like to ask please do not hesitate to contact me in csarantidis@ionio.gr

