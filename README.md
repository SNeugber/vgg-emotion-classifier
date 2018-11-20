# VGG Emotion Classifier

Attempt to use a pretrained VGG model as described [here](https://github.com/tensorflow/models/tree/master/research/audioset) to train a classifier using the [RAVDESS](https://smartlaboratory.org/ravdess/) emotion dataset.

## Setup

1. Download the pretrained VGG model from [here](https://storage.googleapis.com/audioset/vggish_model.ckpt)
1. Move the VGG model into `./pretrained_models/`
1. Download the RAVDESS speech dataset from [here](https://zenodo.org/record/1188976/files/Audio_Speech_Actors_01-24.zip?download=1)
1. Extract the zip into `./data`
1. Install [conda](https://conda.io/)
1. Install dependencies: `conda env create -f environment.yml`
1. Activate environment: `source activate vggec`
1. Run jupyter: `jupyter notebook`

## Project Structure

Notebooks with the relevant code can be found in `experiments`
