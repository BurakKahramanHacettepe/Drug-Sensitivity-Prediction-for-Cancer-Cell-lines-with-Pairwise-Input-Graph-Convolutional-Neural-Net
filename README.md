## Getting Started

---

Below there are 4 colab links for our project

0. Cell-Line Data Preprocessing ipynb files can be found in repository

1. *Colab Link For Cell-Line Data Setup :* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15xXZXPFaefLk2Fk8mKxuX3ULz3AALF49?usp=sharing)

2. *Colab Link For Encoding Cell line vectors :* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CWxLqr4RZcas22ywEbw1MOeuG16ndEJQ?usp=sharing)

3. *Colab Link For Featurizing Molecules :* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1IPLdajMGi6n0P9gwTNoavcVbv4Ww1cfK?usp=sharing)

4. *Colab Link For Fully Connected Final NN :* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ID_Z0yL42l2bw9TuzsKmGnD0HLpulfdh?usp=sharing)



---

Files that are larger then 100MB are below.(rest can be found in git repository)

*Molecule Vectors:* https://drive.google.com/file/d/1-78H4M7MFpfbDyRF2Tat-DPHrbzaWZ9Y/view

*Final data :* https://drive.google.com/file/d/1q8_qgsoYWT3-YpR0mpYJswbEllGliQ4G/view

## Built With

* [Deepchem](https://deepchem.readthedocs.io/en/latest/) - Open-Source Tools for Drug Discovery
* [RdKit](https://www.rdkit.org/) - Open-Source Cheminformatics Software
* [Keras-Tensorflow](https://www.tensorflow.org/) - An end-to-end open source machine learning platform
---
# Drug-Sensitivity-Prediction-for-Cancer-Cell-lines-with-Pairwise-Input-Graph-Convolutional-Neural-Net



| Student Number(s)                | Student Name(s)                                             |
|----------------------------------|-------------------------------------------------------------|
| 21627284<br>21627394<br>32401068 | Ezgi Naz GÜNGÖR<br>Ahmet Burak KAHRAMAN<br>Fatma Nisa HOPCU |
| **Supervisor(s)**                 | **Company Representative(s)**                                   |
| Asst. Prof. Dr. Tunca DOĞAN      |       

## *ABSTRACT*

Automated prediction of the inhibiting activity of drugs (and drug candidate molecules) on highly resistant cancer cells is an important problem in biomedical research. It is not possible to complete this task solely by biological experiments due to extremely high dataset sizes (i.e., the combination of hundreds of different cancer cell types and billions of possible drug candidate molecules). In this project, a new approach is proposed to tackle this problem by modelling the cancer cell-lines in large scale using genomic and transcriptional features, together with drugs (and drug candidate molecules), and constructing a graph convolutional deep neural network architecture that accepts the features of both drugs and cell-lines at the input level and predicts the activity of the drug (in terms of the real lethal dose that kills the input cancer cell-line). The results of this study may identify potential molecules that can become effective drugs for certain cancer types in the future.

## Method

![ProjectDiagram](https://i.imgur.com/ILjKRP8.png)

What we did in this project can be explained in 4 parts as shown in the figure 
