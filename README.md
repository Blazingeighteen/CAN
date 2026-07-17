# CAN
This repo is the official implementation of the paper "CAN: Context-aware Alignment Network for Weakly Supervised Referring Expression Comprehension"![image](https://github.com/Blazingeighteen/CAN/blob/main/pic2.png)

# Project structure
The directory structure of the project looks like this:

```
├── README.md            <- The top-level README for developers using this project.
│
├── config               <- configuration 
│
├── data
│   ├── anns            <- note: cat_name.json is for prompt template usage
│
├── datasets               <- dataloader file
│
│
├── models  <- Source code for use in this project.
│   │
│   ├── language_encoder.py             <- encoder for images' text descriptions 
│   ├── network_blocks.py               <- files included essential model blocks 
│   ├── fourier_transfer.py                  <- Region Relation Enhancement mechanism  
│   ├── visual_encoder.py               <- visual backbone
│   ├── triplet_loss.py               <- triplet_loss
│   │
│   │
│   ├── CAN           <- most important files for DViN model implementations
│   │   ├── __init__.py
│   │   ├── head.py   <- for anchor-prompt contrastive loss
|   |   ├── net.py    <- main code for DViN model
│   │
│   │
├── utils  <- hepler functions
├── requirements.txt     <- The requirements file for reproducing the analysis environment
│── train.py   <- script for training the model
│── test.py <- script for testing from a model
│
└── LICENSE              <- Open-source license if one is chosen
```

Our code will be available after be accepted.
