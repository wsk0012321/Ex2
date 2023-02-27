The program runs on the pretrained word embedding models, which is attached. The code for training word embedding is also inclued, but we highly recommended to load the pretrained ones, but in case that you need to use this training process, please upgrade the numpy to latest version:
   
    pip install --upgrade numpy
    
    For running the main project, please first manually register the pretrained models:
    
    python -m spacy init vectors (1.)sv (2.)D:/embeddings/sv_talbanken.txt (3.)D:/models/sv --name model
    
    You may need to edit the command and execute it:
    
    1. sv for Swedish and en for English\n",
    2. your path of pretrained model\n",
    3. the directory where you want to save the model
  
The annotated data for train and test is included.
