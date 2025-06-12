# KNN Iris Classifier

This project is a simple implementation of the K-Nearest Neighbors (KNN) algorithm to classify Iris flower species based on the [Iris.csv](d:/Downloads/knn/Iris.csv) dataset.

## Project Structure

- [Knn.py](d:/Downloads/knn/Knn.py): Main Python script to run the KNN classification.
- [Iris.csv](d:/Downloads/knn/Iris.csv): Iris dataset containing sepal and petal length and width data for three Iris species.
- [.gitattributes](d:/Downloads/knn/.gitattributes): Git configuration file.

## How to Run

1. Make sure Python 2.x is installed on your computer.
2. Run the script with the following command in the terminal:
    ```sh
    python Knn.py
    ```
3. Enter the value of `K` (number of nearest neighbors) and the flower features (Sepal Length, Sepal Width, Petal Length, Petal Width) as prompted.

## Notes

- This script uses Python 2.x (uses `input` and print syntax without parentheses).
- The dataset must be in the same directory as the script.

## Example Usage

```
K: 3
Sepal Length: 5.1
Sepal Width: 3.5
Petal Length: 1.4
Petal Width: 0.2
```

The script will display the predicted species based on the input data.
