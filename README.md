Thank you for your interest in our work, we have done a initial release of our code and dataset. 

Run non-batch version:
```
cd code/
CUDA_VISIBLE_DEVICES=0 python -u main_semi_crf.py > log.mtref
```

Run batched version:
```
cd code/
CUDA_VISIBLE_DEVICES=0 python -u neural_jacana.py --batchsize 1 --max_span_size 4 > log.mtref
```

The paper can be found on [arXiv](https://arxiv.org/pdf/2106.02569.pdf).
