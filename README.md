# SPAM EMAIL FILTERING WITH NAIVE BAYES AND SVM

## Project Overview

This project implements a **spam email classification system** using **Naive Bayes (NB)** and **Support Vector Machine (SVM)** algorithms. The objective is to accurately distinguish between spam and legitimate (ham) emails using supervised machine learning techniques and real-world email datasets.

The system is designed for experimentation, learning, and evaluation of classical machine learning models applied to text classification problems. It includes dataset preparation, training, evaluation, and visualization of model performance.

The project was developed using **Visual Studio** with the **Jupyter Notebook extension**, enabling both interactive analysis and structured development.

---

## Features

* Spam vs Ham email classification
* Naive Bayes and Support Vector Machine models
* Automatic dataset handling (local copy or online download)
* Model accuracy evaluation
* Data visualization support
* Modular and easy-to-extend code structure

---

## Dataset

The project uses the **Apache SpamAssassin Public Corpus**, a widely used benchmark dataset for spam filtering research.

The following datasets are utilized:

* `easy_ham`
* `easy_ham_2`
* `hard_ham`
* `spam`
* `spam_2`

If the dataset files are not available locally, the system automatically downloads them from the official SpamAssassin repository.

---

## Installation

### 1. Clone or Download the Repository

```bash
git clone https://github.com/your-username/SPAM-EMAIL-FILTERING-WITH-NB-AND-SVM.git
```

Or download the ZIP file and extract it to your local machine.

---

### 2. Environment Setup

* Python **3.8 or higher** is recommended
* Developed using **Visual Studio** with the **Jupyter Notebook extension**
* Works on Windows, Linux, and macOS (paths may need adjustment)

---

### 3. Directory Structure

The script automatically creates required directories if they do not exist:

```
PROJECT/
└── data/
    └── spam data/
```

Dataset files are copied or downloaded into the `spam data` folder.

---

### 4. System Requirements

* **Minimum 16 GB RAM** recommended for training and accuracy analysis on large datasets
* **Internet connection required** only for:

  * Downloading datasets (if not available locally)
  * Generating visualizations

The classification pipeline itself can run offline once the data is available.

---

## Dependencies

### Standard Python Libraries

The following libraries are part of Python’s standard library and require no additional installation:

* `os`
* `shutil`
* `urllib.request`

### Machine Learning & Visualization Libraries

Install required third-party libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

---

## Usage

1. Open the project in **Visual Studio** or any Jupyter-compatible environment
2. Run the dataset preparation script to load or download the email corpus
3. Execute the notebooks to:

   * Preprocess email text
   * Train Naive Bayes and SVM models
   * Evaluate accuracy and performance
   * Visualize results

---

## Notes

* Ensure file paths match your local system configuration
* Large datasets may require increased memory for smooth execution
* The project is suitable for academic work, experimentation, and learning purposes

---

## Future Improvements

* Hyperparameter tuning
* Deep learning-based text classification
* Deployment as a web or API-based service
* Real-time email filtering integration

---

## License

This project is intended for educational and research purposes.

Feel free to explore, modify, and improve the system.

---

Good luck, and happy experimenting 
Cheers
Oshim ThankGod Jasper
(Brooklynboss)
