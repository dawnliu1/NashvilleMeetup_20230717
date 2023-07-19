# A Practical Guide to Training and Fine-Tuning Language Models 
#### Nashville Data Science Meetup
#### July 17th, 2023

This repo includes the example code which was shown in Nashville Data Science Meetup. The original presentation can be access here: [Presentation](NashvilleMeetUp_20230717.pdf).
The example code to fine-tuning pre-trained model and train your own tokenizer and masked language model are included. 
The dataset is not provided. You can download from Hugging Face dataset hub by yourself with load_dataset function.

## Instructions

Install the dependencies listed in requirements.txt. This work was done in a Python 3.8 kernel.

I suggest creating a Python virtual environment or using a [Docker image](https://hub.docker.com/r/pytorch/pytorch) with Cuda/PyTorch already configured.

## Datasets

- CNN news dataset: https://huggingface.co/datasets/AyoubChLin/CNN_News_Articles_2011-2022
- OpenWebText dataset: https://huggingface.co/datasets/Skylion007/openwebtext

## Contact

Liming Zhou (limzhouiu@gmail.com)