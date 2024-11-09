#### This repository contains the source code used for our research paper, "Malaria Parasite Detection in Microscopic Blood Smear Images Using Deep Learning Techniques." 

#Abstract

Malaria remains a curable illness causing a significant number of deaths globally. Timely and accurate detection is crucial for prompt patient management. This research proposes a highly effective and precise Convolutional Neural Network (CNN) model designed specifically for detecting malaria parasites (MPD). Furthermore, two cutting-edge deep learning (DL) models, DenseNet121 and VGG16, were fine-tuned for MPD. The developed CNN model was trained using blood smear images and achieved notable performance: a classification accuracy of 96.66%, precision of 97.09%, F1-score of 96.56%, and sensitivity of 96.03%. A comprehensive analysis demonstrates that the proposed CNN model yields comparable accuracy to DenseNet121 and VGG16 while possessing notably fewer trainable parameters. This suggests that the proposed CNN model is more efficient and less complex than the pre-trained DenseNet121 and VGG16 models. Additionally, the proposed CNN technique surpasses the performance of three earlier investigations in MPD. Moreover, this paper presents heat maps as an explainable AI technique, highlighting significant regions and image patterns that significantly influence DL model decisions. Overall, the findings underscore the potential of DL algorithms in detecting malaria parasites, potentially aiding medical practitioners in administering timely treatments to millions affected by the disease.



we implemented the code using Jupyter Notebook, which can be advantageous for those looking to replicate our experiments or learn from it.

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






@inproceedings{foulefack2024malaria,
  title={Malaria Parasite Detection in Microscopic Blood Smear Images Using Deep Learning Techniques},
  author={Foulefack, Rosma{\"e}l Zidane Lekeufack and Akinyelu, Andronicus A and Ranirina, Dinna and Mpinda, Berthine N},
  booktitle={2024 International Joint Conference on Neural Networks (IJCNN)},
  pages={1--8},
  year={2024},
  organization={IEEE}
}
