# Bias_Word_Embeddings
This project aims at exploring Bias in Word Embeddings and the techniques for debiasing the data-set. A list of references are given at the end that were referred to in the project.

### Introduction
Word Embeddings are one of the most popular representations of words that are used in various Natural Language Processing tasks. However they inherently contain multiple types of biases that can greatly affect the outcome of the algorithms and systems in which these word embeddings are used. This project aims to identify biases pertaining to gender, race and religion and attempt to debias them using traditional methods like hard debiasing (Bolukbasi et al.). The project also explores the clustering of words having similar kinds of bias in line of work done by Hila et al. More details about the project can be found in the *Documentation* sub-directory. 

### Files and directory structure
The following is a brief description of the various files and directories in this repository

1. **Code:** This sub-directory contains the pretrained word embeddings (from Thomas Manzini, et al.) as well as text files containing words pertaining to profession and some common words. It also contains two Jupyter notebooks, one containing the code for the project and the other exploring word embeddings for Google News dataset. 
2. **Documentation:** This sub-directory contains the project presentation, the project report and the initial project write-up in their respective sub-directories.
3. **Presentation_Research_Paper:** This sub-directory contains a presentation on the paper - "Lipstick on a Pig: Debiasing methods cover up systematic gender biases
in word embeddings but do not remove them" by Hila Gonen and Yoav Goldberg. This paper was referred to in the project as well.
4. **Resources:** This sub-directory contains a few papers that were referred to during the course of the project.
5. **Readme:** This file contains a very brief description about the project and the repository.

### References
1. Hila Gonen, Yoav Goldberg, *Lipstick on a Pig: Debiasing methods cover up systematic gender biases in word embeddings but do not remove them*, https://arxiv.org/pdf/1903.03862.pdf
2. Tolga Bolukbasi, et al., *Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings*, https://arxiv.org/pdf/1607.06520.pdf
3. Jieyu Zhao, et al., *Learning Gender-Neutral Word Embeddings*, https://arxiv.org/pdf/1809.01496.pdf
4. Sevtap Duman, et al., *(Visualization of) gender bias in word embeddings*, http://wordbias.umiacs.umd.edu/
5. Aylin Caliskan, et al., *Semantics derived automatically from language corpora contain human-like biases*, https://arxiv.org/pdf/1608.07187.pdf
6. Nikhil Garg, et al., *Word embeddings quantify 100 years of gender and ethnic stereotypes*, https://arxiv.org/pdf/1711.08412.pdf
7. Thomas Manzini, et al., *Black is to Criminal as Caucasian is to Police:Detecting and Removing Multiclass Bias in Word Embeddings*, https://arxiv.org/pdf/1904.04047v1.pdf
8. Harini Suresh, John V. Guttag, *A Framework for Understanding Unintended Consequences of Machine Learning*, https://arxiv.org/pdf/1901.10002.pdf
9. Alex Fefegha, *Racial Bias and Gender Bias Examples in AI systems*, https://peopleofcolorintech.com/articles/racial-bias-and-gender-bias-examples-in-ai-systems/
10. Marianne Bertrand, Sendhil Mullainathan, *Are Emily and Greg More Employable than Lakisha and Jamal? A Field Experiment on LaborMarket Discrimination*, https://www2.econ.iastate.edu/classes/econ321/Orazem/bertrand_emily.pdf
11. Thomas Manzini, et al., *Debiasing Multiclass Word Embeddings*, https://github.com/TManzini/DebiasMulticlassWordEmbedding
12. Ella Rabinovich, Shuly Wintner, *The Reddit-L2 corpus*, http://cl.haifa.ac.il/projects/L2/
