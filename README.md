# Segformer
Here is the code of my project on segformer for the course of Deep Learning

I used the Hugging Face repository called **Transformers** and modified its code to test my variants. In order not to break the installation process (which is necessary for you to test the code and for me, since I had to reinstall the repository with pip so that the module recognizes my modifications), I did not remove or clean up unnecessary files. This document explains how to use the code and where to find the modifications that document my work.

## Files to Examine

The important file is the notebook located in the `hf_proj` folder, named `sergformer.ipynb`. This is where I trained and evaluated my models.

To review the changes I made, navigate to the directory `hf_proj/Modified_File`, which contains copies of the final versions of the modified files. The added code sections are delimited by the comment:
/!\ added code by student


I mainly modified the `SegformerDecodeHead` class in the file `modeling_segformer.py` (around line 675) as well as the `SegformerConfig` class in the file `configuration_segformer`.

## Access to the Dataset

The dataset is freely accessible on Hugging Face, but you will need a Hugging Face account and a token (which is free) to access it. Since I do not know if you have an account, I have provided a token that will be deactivated at the end of the semester. If you need to run the notebook, you will need to copy and paste the token (instructions will be provided in the notebook).

token = see the report

## Installation

The repository should be installed following the instructions provided in the [Hugging Face Transformers repository](https://github.com/huggingface/transformers).
In particular download this repo and use **pip install .** on the directory HF_SEGFORMER.

Alternatively, if you prefer another method, there is a `requir.txt` file in the `hf_proj` directory that lists all the dependencies.
