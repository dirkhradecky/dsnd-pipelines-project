# Fashion Forward Forecasting

In this project a machine learning model will analyze several data of a purchase (for example text of the review, customer age and product category). The aim is to predict if a customer would recommend a product or not.

## Getting Started

Instructions for how to get a copy of the project running on your local machine.

### Dependencies

```
scikit-learn
pandas
spacy
notebook
torch
transformers
```

### Installation

#### Clone the github Repository

Go to a directory you prefer the project to be and run the following command

```
git clone https://github.com/dirkhradecky/dsnd-pipelines-project.git
```

Then open the directory

```
cd dsnd-pipelines-project
```

#### Create project and environment

A simple possibility to create a project and a virtual environment would be to use uv.

If you don't have uv installed you can get infos about how to install it here: [Installing uv](https://docs.astral.sh/uv/getting-started/installation/)

If uv is installed, first initialize a project with the following command

```
uv init
```

Then create a virtual environment with all the dependencies

```
uv sync
```

Alternatively you can, of course, use pip and the requirements.txt to install the necessary dependencies.

You can find the Jupyter notebook in the 'starter' directory.

## Testing

There are no tests needed for this project.

## Project Instructions

In the notebook the following is done:

- Loading and inspecting the data
- Data Exploration
- Building a full pipeline of:
  - Preprocessing
  - Feature Engineering
  - Training
- Fine-Tuning the model

## Built With

- scikit-learn
- spaCy
- Pytorch
- pandas
- transformers (Hugging Face)

## License

[License](LICENSE.txt)
