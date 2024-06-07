#### This repository contains the source code used for our research paper, "Malaria Parasite Detection in Microscopic Blood Smear Images Using Deep Learning Techniques." In this paper, we investigate the use of two pre-trained deep learning models, DenseNet121 and VGG-16, for detecting malaria parasites. Additionally, we propose a simpler CNN architecture for the same task, which has achieved results comparable to those of established models in the literature.

As beginner programmers, we implemented the code using Jupyter Notebook, which can be advantageous for those looking to replicate our experiments or learn from it.

### Replication Process:

1- Clone the repository.

git clone https://github.com/RosmaelZidane/CNN-MPD.git

cd CNN-MPD

2- Create a virtual environment.

python -m venv .myvenv

3- Activate the virtual environment.

source activate .myvenv

4- Install the necessary libraries.

pip install -r requirements.txt

5- Open Jupyter Notebook and select the appropriate Python interpreter.

jupyter-notebook

6- Download the dataset using the link provided in the paper and save it to your computer.

7- Update the data reading path in the notebook to reflect the dataset's location on your computer, then run the code (MPD_With_CNN) from the top.

By following these steps, you can replicate our experiments and verify the results presented in our paper.
