# Knowledge Graph Embedding with Paired Relations Rotation and Entities Adjustment by Quaternions
This is the code of paper **Knowledge Graph Embedding with Paired Relations Rotation and Entities Adjustment by Quaternions.**

## Dependencies
- Python 3.7+
- [PyTorch](http://pytorch.org/) 1.0+


## Running the code 

### Notice
```
QuatPE1: with two part
QuatPE2: only use paired relations
QuatPE3: only use entities adjustment vectors
```

To reproduce the results of these models, run the following commands.

### WN18RR
```
# QuatPE1
python train_QuatPE1_WN18RR.py

# QuatPE2
python train_QuatPE2_WN18RR.py

# QuatPE3
python train_QuatPE3_WN18RR.py
```

### FB15K-237
```
# QuatPE1
python train_QuatPE1_FB15K237.py

# QuatPE2
python train_QuatPE2_FB15K237.py

# QuatPE3
python train_QuatPE3_FB15K237.py
```


## Acknowledgement
This code is based on the [QuatE](https://github.com/cheungdaven/QuatE), [OpenKE](https://github.com/thunlp/OpenKE), and  [QuatDE](https://github.com/hopkin-ghp/QuatDE). Thanks for their contributions.
