# course_evals

A filter that removes unconstructive comments from student course evaluations

## Installation

This code is currently housed in a .ipynb file (one optimized for Colab, the other for Jupyter).
As framed, it doesn't require installation other than opening it in Colab or Jupyter in an otherwise empty folder.
Add your course evals to the folder, preferably as a .docx file, and "run all".

## Features

- This code uses a natural language processing model to flag comments as "constructive" or "unconstructive."
- It filters out comments flagged as unconstructive and writes the constructive comments to a new .docx file in a "results" folder.
- It currently accepts .docx, .pdf, and .txt files, though .docx seems to give the best results.

## Dependencies

- The package directly uses ktrain, tensorflow, python-docx, and textract in addition to native Python 3 and common packages.  Many of these in turn have a fair few dependencies of their own.

## Usage

- Use use self-contained Colab page at https://colab.research.google.com/drive/1Nd5IlNJcT07Wm7x_DT1Np0NMuqnexMYr?usp=sharing
or
- Download the Colab .ipynb file, and run it in your Google Drive
or
- Download the Jupyter .ipynb file and run it locally on your computer.  This may require additional package/library installations via conda, pip, etc.

- Please note: this program depends on internet access to download the model.


## Contributors

We welcome and recognize all contributions.

### Credits
This package makes heavy use of ktrain.

https://arxiv.org/abs/2004.10703

@article{maiya2020ktrain,
    title={ktrain: A Low-Code Library for Augmented Machine Learning},
    author={Arun S. Maiya},
    year={2020},
    eprint={2004.10703},
    archivePrefix={arXiv},
    primaryClass={cs.LG},
    journal={arXiv preprint arXiv:2004.10703},
}
