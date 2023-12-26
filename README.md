## SelfVQA - Visual Question Answering with Self-Supervision

### Project Description:
SelfVQA is an innovative project that explores the realm of Visual Question Answering (VQA) through the lens of self-supervised learning techniques. The goal of this project is to develop a robust model capable of answering questions about images, leveraging self-supervision to enhance its understanding of visual content.


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

## Title: SelfVQA - Visual Question Answering with Self-Supervision

### Project Description:
SelfVQA is an innovative project that explores the realm of Visual Question Answering (VQA) through the lens of self-supervised learning techniques. The goal of this project is to develop a robust model capable of answering questions about images, leveraging self-supervision to enhance its understanding of visual content.

### Key Features:
- **Self-Supervised Learning:** Utilize self-supervised learning strategies to enhance the model's comprehension of visual information without relying on external labeled datasets.
  
- **Deep Neural Networks:** Implement state-of-the-art deep neural networks to extract meaningful features from images and questions, fostering a more nuanced understanding of the relationship between visual and textual elements.

- **Interactive Question-Answering Interface:** Showcase the model's capabilities through an interactive interface where users can input questions related to provided images and witness the model's responses.

- **Adaptability:** The architecture is designed to be adaptable to various image datasets, ensuring flexibility for different applications and domains.

### How to Use:
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/smn06/selfvqa.git
   cd selfvqa
   ```

2. **Setup Environment:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download Pre-trained Models:**
   Download pre-trained models for image feature extraction and question embedding from [link-to-be-provided] and place them in the `models` directory.

4. **Run the Demo:**
   Execute the demo script to interact with the model:
   ```bash
   python demo.py
   ```

### License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

