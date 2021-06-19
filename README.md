# Early identification of online user's financial fraud


## Running Environment

The main packages you need to install

```
1. python 2.7 
2. tensorflow 1.5.0
```

## DateSet
For experiments, we have run **SAFE** on two real-world datasets: twitter and wiki which have been attached in [twitter/](https://github.com/PanpanZheng/SAFE/tree/master/twitter) and [wiki/](https://github.com/PanpanZheng/SAFE/tree/master/wiki), respectively.


## Model Evaluation

The command lines for SAFE and baselines go as follow

* **SAFE** 
```
    python models/safe.py $1
```

* **M-LSTM** 

```
    python models/base_rnn.py $1
```

* **CPH & SVM** 

```
    python models/safe_baselines.py $1
```

**where** *$1* refers to datasets on which the model runs, and it can be assigned as 'twitter' or 'wiki'.
