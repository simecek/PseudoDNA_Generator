## Language Models

### Intergenomic 50k dataset

* [**AWD_LSTM_v0**](https://drive.google.com/open?id=1-12oC5ParyeYSR8QC91raIIWc6WatP7p): the first AWD-LSTM model trained on all chromosomes except chr1 and chr2
* [**AWD_LSTM_v1**](https://drive.google.com/open?id=1Cgzsnmpr8l1tAMHYd8wauCrf0ORg36Rq): AWD-LSTM model trained on all chromosomes except chr1 and chr2 with FP16 precision, no difference observed (not faster, not smaller file)
* [**AWD_LSTM_v2**](https://drive.google.com/open?id=1-2SA3blCXh5aVt0ACTMZWU3OJvQtUKbi): AWD-LSTM model trained on all chromosomes except chr1 and chr2 with higher dropout (0.5 instead 0.3), no difference observed,  [Intergenomic_AWD_LSTM_v2.ipynb](Intergenomic_AWD_LSTM_v2.ipynb) is a script used for training
* [**AWD_LSTM_v4**](https://drive.google.com/open?id=1EdXaCVg8ghUy8026S7aX271bguRliNZk): AWD-LSTM model trained on all chromosomes except chr1, the basic benchmark, [Intergenomic_AWD_LSTM_v4.ipynb](Intergenomic_AWD_LSTM_v4.ipynb) is a script used for training, accuracy **42.1**
* [**AWD_LSTM_v5**](https://drive.google.com/file/d/18gz2eCeJ9rxcbyHdwvYBNP73RBdWJ8uu/view?usp=sharing): AWD-LSTM model trained on all chromosomes except chr1, new tokenizer (bos excluded), [Intergenomic_AWD_LSTM_v5.ipynb](Intergenomic_AWD_LSTM_v5.ipynb) is a script used for training, accuracy **41.8**
* [**AWD_LSTM_v6**](https://drive.google.com/file/d/1Z6cp4wFa7Z4Rys8eUqfuE6Qsv4xlh13C/view?usp=sharing): AWD-LSTM model trained on all chromosomes except chr1, 10 epochs with lr=0.01, [Intergenomic_AWD_LSTM_v6.ipynb](Intergenomic_AWD_LSTM_v6.ipynb) is a script used for training, accuracy **43.2**
* [**AWD_LSTM_v7**](https://drive.google.com/file/d/1TAq-V3LArGhGr1qhbYZJSpqzpqe3d2jH/view?usp=sharing): AWD-LSTM model trained on all chromosomes except chr1, only 5 epochs with lr=0.01, [Intergenomic_AWD_LSTM_v7.ipynb](Intergenomic_AWD_LSTM_v7.ipynb) is a script used for training, accuracy **42.1**
* [**Intergenomic_WholeGenomeButChr1_v1_0**](https://drive.google.com/file/d/1-6JRgW7m1fwwyE9AavR-8Tl_3oGNkjoR/view?usp=sharing): Finetuned AWD-LSTM model, previously trained on 25% of the whole genome, [Intergenomic_WholeGenomeButChr1_v1_0.ipynb](Intergenomic_WholeGenomeButChr1_v1_0.ipynb) is a script used for training, accuracy **42.9**
* [**Intergenomic_WholeGenomeButChr1_v2_0**](https://drive.google.com/file/d/1HH1bZYmo-XJxFKZ2XVkdWJFNHgpt9ucB/view?usp=sharing): Finetuned AWD-LSTM model, previously trained on 25% of the whole genome, no bos token [Intergenomic_WholeGenomeButChr1_v2_0.ipynb](Intergenomic_WholeGenomeButChr1_v2_0.ipynb) is a script used for training, accuracy **42.3**

### Exons 50k dataset  

* **Exons_AWD_LSTM_v0**: AWD-LSTM model trained on all chromosomes except chr1, 5 epochs with lr=0.01, [Exons_AWD_LSTM_v0.ipynb](Exons_AWD_LSTM_v0.ipynb) is the script used for training, accuracy **35.9**
* **Exons_AWD_LSTM_v1**: AWD-LSTM model trained on all chromosomes except chr1, 5 epochs with lr=0.05, [Exons_AWD_LSTM_v1.ipynb](Exons_AWD_LSTM_v1.ipynb) is the script used for training, accuracy **35.8**
* **Exons_WholeGenomeButChr1_v1_0**: Finetuned AWD-LSTM model, previously trained on 25% of the whole genome, no bos token [Exons_WholeGenomeButChr1_v1_0.ipynb](Exons_WholeGenomeButChr1_v1_0.ipynb) is a script used for training, accuracy **36.3**

### Transcripts (coding sequence) dataset 

* **Transcripts_AWD_LSTM_v0**: AWD-LSTM model trained on all chromosomes except chr1, 5 epochs with lr=0.01, [Transcripts_AWD_LSTM_v0.ipynb](Transcripts_AWD_LSTM_v0.ipynb) is the script used for training, accuracy **36.5**

### 3'UTR 50k dataset 

* **3UTR_AWD_LSTM_v0**: AWD-LSTM model trained on all chromosomes except chr1, 5 epochs with lr=0.01, [3UTR_AWD_LSTM_v0.ipynb](3UTR_AWD_LSTM_v0.ipynb) is the script used for training, accuracy **36.5**

### 5'UTR 25k dataset 

* **5UTR_AWD_LSTM_v0**: AWD-LSTM model trained on all chromosomes except chr1, 5 epochs with lr=0.01, [5UTR_AWD_LSTM_v0.ipynb](5UTR_AWD_LSTM_v0.ipynb) is the script used for training, accuracy **37.6**

### Introns 50k dataset

* **Introns_AWD_LSTM_v0**: AWD-LSTM model trained on all chromosomes except chr1, 5 epochs with lr=0.01, [Introns_AWD_LSTM_v0.ipynb](Introns_AWD_LSTM_v0.ipynb) is the script used for training, accuracy **41.6**
