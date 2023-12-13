# Exploring Deepfake Detection with MesoNet

"Deepfakes" refer to fake media, like pictures and videos, that are developed using deep neural networks. Unlike fake media created using Photoshop, these forgeries are _almost indistinguishable_ from the real thing.

In this project, we explore the world of Deepfakes using a model engineered to detect them, known as MesoNet.

The MesoNet research paper was published by [Darius Afchar](https://arxiv.org/search/cs?searchtype=author&query=Afchar%2C+D), [Vincent Nozick](https://arxiv.org/search/cs?searchtype=author&query=Nozick%2C+V), [Junichi Yamagishi](https://arxiv.org/search/cs?searchtype=author&query=Yamagishi%2C+J), and [Isao Echizen](https://arxiv.org/search/cs?searchtype=author&query=Echizen%2C+I) in September 2018.
The paper includes two models each trained on two different datasets: we explore the Meso4 model trained on the Deepfake dataset, which was created and released by MesoNet researchers.
- Paper: [MesoNet: a Compact Facial Video Forgery Detection Network](https://arxiv.org/abs/1809.00888)
- GitHub repo: [DariusAf/MesoNet](https://github.com/DariusAf/MesoNet)

The Meso4 model is designed for binary classification to identify real and deepfake images.

Deepfake research rapidly evolves, and we suggest keeping up with the latest research using tools like [Google Scholar](https://scholar.google.com/scholar)

_Usage Guideline_

Install the required dependencies

Clone the repository:
git clone https://github.com/your-username/your-repository.git
cd your-repository


Extract the dataset:s

The script assumes that your dataset is stored in a zip file named 'data.zip'. If your dataset is stored differently, make sure to adjust the file path in the script accordingly.

Load the pre-trained Meso4 model

Run the deepfake detection

The model's predictions are visualized using the plotter function. The plots include correctly classified real and deepfake images as well as misclassified instances.

Feel free to contribute to the project by opening issues or creating pull requests.

