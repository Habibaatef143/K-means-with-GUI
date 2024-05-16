# K-Means Clustering Application

This application performs K-Means clustering on a dataset and provides various evaluation metrics for the clustering results. It uses the Tkinter library for the graphical user interface (GUI) and the scikit-learn library for performing the clustering.

## Prerequisites

Before running the code, make sure you have the following dependencies installed:

- Python 3.x
- scikit-learn
- pandas
- numpy
- seaborn
- matplotlib

## Installation

1. Clone the repository or download the code files.
2. Install the required dependencies by running the following command:
pip install scikit-learn pandas numpy seaborn matplotlib
## Usage

1. Open a terminal or command prompt and navigate to the directory where the code files are located.
2. Run the following command to execute the application:
python <DataMinig>.py
3. The application window will open, and you will be prompted to input the number of clusters (k) you want to create.
4. Enter a value between 3 and 9 and click the "Clust Data" button.
5. The application will display a scatter plot of the data points and their assigned clusters.
6. The evaluation metrics for the clustering results will be shown below the scatter plot, including SSE (Sum of Squared Errors), Silhouette Score, Davies Bouldin Score, Calinski Harabasz Score, and Correlation Coefficient.
7. You can click the "Show Elbow" button to display the Elbow Method plot, which helps determine the optimal value of k based on the SSE.
8. Click the "Evaluation" button to display a similarity matrix heatmap and calculate the correlation coefficient between the similarity matrix and the incidence matrix.
9. Close the application window to exit.

## Dataset

The application uses the "Mall_Customers.csv" dataset, which should be present in the same directory as the code files. If the dataset file is missing, the application will not run correctly.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to modify the code and adapt it to your needs.

## Acknowledgments

- The code utilizes the scikit-learn, pandas, numpy, seaborn, and matplotlib libraries.
- The K-Means clustering algorithm is based on the scikit-learn implementation.
