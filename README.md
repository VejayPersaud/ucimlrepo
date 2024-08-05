# Getting Started

Simply run `main.ipynb` to run the full data pipeline. It will install the required dependencies and call each subnotebook.

# Project Structure

- `main`: calls end-to-end pipeline
- `data_preprocessing`: identifies features and cleans up data
- `data_exploration`: provides charts / views into dataset distribution
- `model_training`: defines function for training and vanilla models (NN, SVM, RF, KNN)
- `grid_search`: hyperparameter tuning for models
- `ensemble_method`: ensemble method combining models