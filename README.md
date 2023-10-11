<!-- # AIOps-project-DVC-NLP-uscase
AIOps project DVC-NLP-uscase -->

![AIOps-project-DVC-NLP-usecase](https://socialify.git.ci/Oladapoduk/NLP-Project-Classification?language=1&owner=1&name=1&stargazers=1&theme=Light)
* "NLP Classification with MLFlow and DVC" is an innovative project that combines the power of natural language processing (NLP) and machine learning for text classification tasks. MLFlow,
  a versatile machine learning lifecycle management tool, is used to orchestrate the development and deployment of NLP models. Additionally, Data Version Control (DVC) is integrated into the workflow to 
  efficiently manage and version control the large datasets typically associated with NLP tasks. This project aims to streamline the end-to-end process of training, tracking, 
  and deploying NLP classification models, ensuring reproducibility and scalability while handling complex and evolving text data.

* data is available at - [this googele drive link](https://drive.google.com/file/d/13A0RtvZZanHXKZNbz5JKwjjO2FedNQCR/view?usp=sharing)

## Important References - 

* [Bag of Words- Krish Naik](https://youtu.be/D2V1okCEsiE)

* [TF-IDF- Krish Naik](https://youtu.be/D2V1okCEsiE)

* [DVC studio home page](https://studio.iterative.ai/)
## STEPS -

### STEP 01- Create a repository by using template repository

### STEP 02- Clone the new repository

### STEP 03- Create a conda environment after opening the repository in VSCODE

```bash
conda create --prefix ./env python=3.7 -y
```

```bash
conda activate ./env
```
OR
```bash
source activate ./env
```

### STEP 04- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 05- initialize the dvc project
```bash
dvc init
```

### STEP 06- commit and push the changes to the remote repository
