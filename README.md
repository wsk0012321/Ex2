{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "1cf84337",
   "metadata": {},
   "source": [
    "The program runs on the pretrained word embedding models, which is attached. The code for training word embedding is also inclued, but we highly recommended to load the pretrained ones, but in case that you need to use this training process, please upgrade the numpy to latest version:\n",
    "\n",
    "pip install --upgrade numpy\n",
    "\n",
    "For running the main project, please first manually register the pretrained models:\n",
    "\n",
    "!python -m spacy init vectors (1.)sv (2.)D:/embeddings/sv_talbanken.txt (3.)D:/models/sv --name model\n",
    "\n",
    "You may need to edit the command and execute it:\n",
    "\n",
    "1. sv for Swedish and en for English\n",
    "2. your path of pretrained model\n",
    "3. the directory where you want to save the model"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.8"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
