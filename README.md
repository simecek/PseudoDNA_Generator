# Fastai (v2) redesign

The original pivot was written in TF/keras. However, I have started rewriting the code to pytorch/fastai2. To get the benefit of GPU speed, I am mostly working with Google Colab and my code and data files live in my Google Drive folder. This is for sharing purposes / getting myself oriented.

There are three folders:
* **data**: data used for training models and experiments
* **models**: language models (LSTMs, Markov models...) trained in data above or genome in general
* **experiments**: evaluation of models under various settings

The results of experiments are in the following table (visible only with Masaryk University account)
https://docs.google.com/spreadsheets/d/10mbIn3ZpPZtpD35f5dviF08fRRqjfTWg-BFVW0OzpD0/edit?usp=sharing
