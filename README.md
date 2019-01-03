# Sequential-Neural-Information-Diffusion-Model-with-Structure-Attention

This repository provides reference codes as described in the paper:

>**A Sequential Neural Information Diffusion Model with Structure Attention.**  
>**Zhitao Wang, Chengyao Chen and Wenjie Li.**  
>**CIKM, 2018.** 

## Environment
The code is implemented with Tensorflow. Requirments:  
&emsp;1. Python 2.7  
&emsp;2. Numpy  
&emsp;3. Tensorflow  
&emsp;4. tqdm (for training process display)   

## Run
Defalut:  

    python train.py  
    
Or run with optional arguments:  

    python train.py -d data/hc-exp -l 0.001 -x 32 -e 64 -b 32 -n 200 -f 5
Chech the arguments as:  

    python train.py -h
    -l, --lr (learning rate)  
    -x, --xdim (embedding dimension)  
    -e, --hdim (hidden dimension)  
    -d, --data (data path)  
    -g, --gpu (gpu id)  
    -b, --bs (batch size)  
    -f, --freq (validation frequency)  
    -n, --nepoch (number of training epochs)

## Citing
    @inproceedings{Wang:2018:SNI:3269206.3269275,
    author = {Wang, Zhitao and Chen, Chengyao and LI, Wenjie},
    title = {A Sequential Neural Information Diffusion Model with Structure Attention},
    booktitle = {Proceedings of the 27th ACM International Conference on Information and Knowledge Management},
    series = {CIKM '18},
    year = {2018},
    location = {Torino, Italy},
    pages = {1795--1798}
    } 


  
