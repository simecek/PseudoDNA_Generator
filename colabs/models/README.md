## Language Models

### Intergenomic 50k dataset

* [**AWD_LSTM_v0**](https://drive.google.com/open?id=1-12oC5ParyeYSR8QC91raIIWc6WatP7p): the first AWD-LSTM model trained on all chromosomes except chr1 and chr2
* [**AWD_LSTM_v1**](https://drive.google.com/open?id=1Cgzsnmpr8l1tAMHYd8wauCrf0ORg36Rq): AWD-LSTM model trained on all chromosomes except chr1 and chr2 with FP16 precision, no difference observed (not faster, not smaller file)
* [**AWD_LSTM_v2**](https://drive.google.com/open?id=1-2SA3blCXh5aVt0ACTMZWU3OJvQtUKbi): AWD-LSTM model trained on all chromosomes except chr1 and chr2 with higher dropout (0.5 instead 0.3), no difference observed,  [Intergenomic_AWD_LSTM_v2.ipynb](Intergenomic_AWD_LSTM_v2.ipynb) is a script used for training
* [**AWD_LSTM_v4**](https://drive.google.com/open?id=1EdXaCVg8ghUy8026S7aX271bguRliNZk): AWD-LSTM model trained on all chromosomes except chr1, the basic benchmark, [Intergenomic_AWD_LSTM_v4.ipynb](Intergenomic_AWD_LSTM_v4.ipynb) is a script used for training
