# About
- The colab notebooks here demonstrate how to use the models released by AI4Bharat at Huggingface hub.
- You do not need GPUs for inferencing
- Due to memory constraints, The colab's free tier may not support loading bigger models.
- Use the distilled version of the model where possible
- Some notebooks (say, Named Entity Recognition (NER)) demonstrates training and inferencing steps
- We will keep updating the repo
## Models
1. Translation from English to (22) Indic languages [Notebook](https://colab.research.google.com/drive/1xKnWbWQW_Xz8z42MyORtKqknIF2qHitI?usp=sharing)
   - One Billion Parameters
   - Requires 4+ GB of memory for inference (i.e., intend to use the model for prediction, not for fine-tuning)
   - We demonstrated a use case for one Indic language. However, you can extend it to any Indic language by using an appropriate flag.
2. Translation from English to (22) Indic languages [Notebook](https://colab.research.google.com/drive/1xKnWbWQW_Xz8z42MyORtKqknIF2qHitI?usp=sharing)
   - 200 Million Parameters
   - **Distilled: Yes**
   - Requires 800+ MB of memory for inference 
   - We demonstrated a use case for one Indic language. However, you can extend it to any Indic language by using an appropriate flag.
3. Translation from one Indic language to any Indic language [Notebook](https://colab.research.google.com/drive/1sDTd0yLYIEftrJVH-bR3vfiIEaVyLfR8?usp=sharing)
    - One Billion Parameters
    - Requires 4+ GB of memory for inference 
4. Translation from one Indic language to any Indic language [Notebook](https://colab.research.google.com/drive/1l9MhcO31p2r5XouTBQRaF8RVEfENody8?usp=sharing)
    - 320 Million Parameters
    - **Distilled: Yes**
    - Requires 1.4+ GB of memory for inference 
5. Tanslation from Indic to English language [Notebook](https://colab.research.google.com/drive/1EINB6byjiy9rzVcvsdLGuEt6G6izHYgT?usp=sharing)
    - One Billion Parameters
    - Requires 4+ GB of memory for inference 
6. Tanslation from Indic to English language [Notebook](https://colab.research.google.com/drive/1OSnT4aOvbVJ3EzDOPiAJKFFuYeZ0GMNa?usp=sharing)
    - 200 Million Parameters
    - **Distilled: Yes**
    - Requires 800+ MB of memory for inference 
7. Chat Model in Hindi: Airavata [Notebook](https://colab.research.google.com/drive/14-z2sGU3LranZvcV-o5sLC0UbPWKP2If?usp=sharing)
    - 7 Billion Parameters
    - Requires 16+ GB of memory for inference
8. Fill in the blank in Indic Languages [Notebook](https://colab.research.google.com/drive/16FYSzlApZyvkB_tASfcYqFCmz3qFMEwL?usp=sharing)
    - Requires less than 1 GB for inference
9. Named Entity recognition in 11 languages [Notebook](https://colab.research.google.com/drive/1zc9TGeGVm4AsJECvPvgVY4ECImbnbYvx?usp=sharing)
