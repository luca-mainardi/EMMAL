# Interpretable Sample Selection with Exceptional Model Mining

This project explores an active learning technique integrated with Exceptional Model Mining (EMM) to address the sampling bias present in traditional active learning methods. By identifying subgroups within the unlabeled dataset that deviate significantly from the global model, EMM helps create a more diverse and representative training set, improving model performance under a constrained labeling budget. The project was evaluated on the Pima Indians Diabetes Dataset and demonstrated effectiveness in enhancing the classification accuracy of active learning tasks.

## Getting Started

To get started with this project, follow these steps to set up a virtual environment, install the dependencies, and run the Jupyter Notebook.

### 1. Clone the Repository

Use git to clone the repository
```bash
$ git clone https://github.com/luca-mainardi/EMMAL.git
$ cd active-learning-emm
```

### 2. Set Up a Virtual Environment

You need Python 3.8 or newer. Follow the instructions below to create a virtual environment:

```bash
# Create a virtual environment
$ python3 -m venv venv
```

Activate the virtual environment (Linux/macOS)
```bash
$ source venv/bin/activate
```

Activate the virtual environment (Windows)
```bash
$ .\venv\Scripts\activate
```

### 3. Install Requirements

Once the virtual environment is activated, install the required dependencies:

```bash
# Install all the dependencies listed in requirements.txt
$ pip install -r requirements.txt
```

4. Run the Notebook

Open the notebook AL_EMM.ipynb and run through the cells to explore the implementation and results of the EMM-based active learning method.

## Contributors

Vincent P. Hoogendam - v.p.hoogendam@student.tue.nl

Kalina Bakardzhieva - k.bakardzhieva@student.tue.nl

Luca Mainardi - l.mainardi@student.tue.nl

Luyang Xie - l.xie@student.tue.nl

Rianne M. Schouten - r.m.schouten@tue.nl

