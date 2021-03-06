floripa-imoveis
==============================
Protótipo de um sistema de avaliação para a precificação de imóveis residenciais. 

### Project Structure
```
├── LICENSE
├── README.md          <- The top-level README for this project
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── assets             <- Stores any images, PDFs, or other static assets
│ 
├── data
│   ├── processed      <- The final, processed data sets for modeling
│   └── raw            <- The original, immutable data dump
│
├── deploy             <- Stores any files, configurations related to deploying your model (Dockerfile, etc.)
│ 
├── model_checkpoints  <- Trained and serialized models, model predictions, model summaries, config files
│
├── notebooks          <- Jupyter notebooks for doing exploratory data analysis, analyzing model outputs, etc.
│
├── scripts            <- Single-purpose scripts for functionality such as processing and cleaning data
│
├── tests              <- Tests for the various aspects of the project (data cleanliness, data processing, model training code, etc.)
│
├── Avaliação instantânea de imóveis residencias     <- Source code for use in this project
│   ├── __init__.py    <- Makes Avaliação instantânea de imóveis residencias a Python module
│   │
│   ├── model          <- Stores any relevant modeling code, interfaces, and definitions
│   │   └── __init__.py
│   │
│   ├── server         <- Stores deployment and inference server code
│   │   ├── __init__.py
│   │   └── main.py    <- Main module for running server
│   │
│   ├── utils          <- Stores various utilities used in project 
│   │   ├── __init__.py
│   │
│   ├── train.py       <- Script to run model training
│   └── eval.py        <- Script to run trained model evaluation 
```
