# Machine Learning Classification and Clustering

An academic Python project exploring supervised learning, unsupervised learning and neural networks using rice and Steam game datasets.

## Rice Classification

Classifies rice grains as Cammeo or Osmancik using seven numerical features.

Models explored:
- Logistic Regression
- Decision Tree
- Random Forest
- NumPy neural network forward propagation
- TensorFlow/Keras neural networks

The classification experiments use five-fold cross-validation, parameter comparisons and a held-out test set.

Evaluation includes Accuracy, Precision, Recall, F1 Score, ROC-AUC and confusion matrices.

## Steam Game Clustering

Explores groups of games using price, positive review percentage and total review count.

Methods explored:
- K-Means
- Agglomerative Clustering
- DBSCAN

Analysis includes feature scaling, the elbow method, Silhouette Scores, cluster visualisations and a comparison excluding an extreme observation.

## Keras Experiments

Three controlled experiments compare:
1. A baseline with four hidden neurons.
2. An increase to eight hidden neurons.
3. Eight hidden neurons with Early Stopping.

Training and validation curves show how loss and accuracy change during training.

## Files

- `ass1.ipynb` — project notebook
- `Rice_C_O.csv` — rice classification data
- `steam_games.csv` — Steam game data

## Tools

Python, pandas, NumPy, matplotlib, scikit-learn and TensorFlow/Keras.

## Running the Project

1. Download the notebook and both CSV files.
2. Open `ass1.ipynb` in Google Colab.
3. Upload both CSV files using Colab's Files panel.
4. Check that the filenames match the notebook's loading code.
5. Run the cells in order from top to bottom.

The datasets need to be uploaded again when starting a fresh Colab runtime.
