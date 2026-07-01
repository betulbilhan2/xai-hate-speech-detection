# xai-hate-speech-detection
Explainable AI (XAI) approach for hate speech detection and classification using the HateXplain dataset.
Open In Colab : https://colab.research.google.com/drive/1JtgoZs4StqssAU1RDw2aezzg-pLImDRq?usp=sharing

##  Project Overview
This project focuses on detecting hate speech and offensive language using the **HateXplain** dataset. Additionally, it utilizes **Explainable AI (XAI)** techniques to interpret the model's predictions and understand which words or features contributed most to the decision.
##  Dataset
We used the [HateXplain Dataset](https://github.com/hate-alert/HateXplain), which is the first benchmark hate speech dataset covering multiple aspects of the issue, including token-level rationales.
* Classes: Hate, Offensive, Normal.
##  Technologies & Models Used
* Python
* PyTorch / TensorFlow (Hangisini kullandıysan)
* Hugging Face Transformers (BERT, RoBERTa vs. kullandıysan)
* LIME / SHAP (XAI için hangisini kullandıysan)
##  How to Run
1. Open the `.ipynb` notebook directly in Google Colab using the badge at the top.
2. Install the required dependencies mentioned in the first cell of the notebook.
3. Run the cells sequentially.


