# Getting Started

Simply run `main.ipynb` to run the full data pipeline. It will install the required dependencies via pip and call each subnotebook.

# Project Structure

- `main`: calls end-to-end pipeline
- `data_exploration`: provides charts / views into dataset distribution
- `data_preprocessing`: prepares data for training
- `model_training`: defines function for training and vanilla models (NN, SVM, RF, KNN)
- `grid_search`: hyperparameter tuning for models
- `ensemble_method`: ensemble method combining models