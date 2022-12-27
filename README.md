# MSc Dissertation UOR 2022



## Getting started

- The project was developed on Colab and so needs to be run on Colab.
- The dataset used has not been provided, neither has the corrected files during experimentation due to Data Privacy restrictions. That means the project won't run. 
- You need to download BioSentVec_PubMed_MIMICIII-bigram_d700.bin, bioword2vec_model.file and BioWordVec_PubMed_MIMICIII_d200.vec.bin and save it to the /files directory. These files are used by vec_embeddings.py.
- Links: https://github.com/ncbi-nlp/BioWordVec, https://github.com/ncbi-nlp/BioSentVec

## Pre-requisites

- On Google Colab, follow the instructions of PRE-REQUISITES.ipynb.
- Open terminal and execute the main.py file.

```
python main.py
```

## Getting familiar with the files

Primary classes:

- main.py : this is the main script to execute the experiments, you simply need to change the parameters based on the scenario you want to run.
- preprocess: performs all preprocessing and cleaning of the original dataset.
- usl_model.py : contains the model creation code, i.e., creates and runs your clustering models.
- vec_embeddings.py: contains all the vector embeddings used in the experiments.
- evaluation_metrics.py: calculates the metrics scores from the model performance.

Some helper classes:

- data_augmentation.py: contains the code to perform data augmentation on the original dataset.
- pca.py: utility class for dimensionality reduction(pca).
- utils.py: helper functions like read().
- autoencoder: utility class for autoencoder logic.

Other main data science workflows:

- eda.py: contains the code essential for the EDA conducted in the research.
- mscproject.ipynb: where all the magic happened (all experiments were conducted here).
- ai_exploratory_data_analysis_stage.ipynb: EDA was conducted here as well.



## Folders

- Data: contains all the augmented data files for experimentation.
- files: contains the results and files used for experimentation.
- files/sent2vec-master : needed for the vector embedding.
- files/vec_embeddings: Contains all the vector embeddings created during experimentation.
         


