# SortMaster-AI
Sorting Optimization using Genetic Algorithm, PSO, and ANN
This project explores and optimizes sorting algorithms using Genetic Algorithm (GA), Particle Swarm Optimization (PSO), and Artificial Neural Networks (ANN). It evaluates the performance of different sorting algorithms and selects the best algorithm for a given dataset based on execution time.

Table of Contents
Introduction
Features
Technologies Used
Setup and Usage
Project Structure
Results
Visualization
Future Work
License
Introduction
Sorting algorithms are fundamental in computer science and are used in a wide variety of applications. This project leverages Genetic Algorithm (GA) and Particle Swarm Optimization (PSO) to optimize the selection of sorting algorithms for specific datasets. Additionally, an Artificial Neural Network (ANN) is trained to predict the execution time of sorting algorithms based on dataset characteristics.

Features
Sorting Algorithms: Implementation of QuickSort, MergeSort, BubbleSort, and SelectionSort.
Optimization Techniques:
Genetic Algorithm (GA): Simulates natural selection to find the best sorting algorithm.
Particle Swarm Optimization (PSO): Utilizes swarm intelligence for optimization.
Artificial Neural Network (ANN): Predicts sorting times based on dataset features like size and range.
Performance Evaluation: Measures execution time for each sorting algorithm.
Visualization: Graphical comparison of results for optimized sorting performance.
Technologies Used
Python 3.8+
NumPy: For numerical operations.
Matplotlib: For visualizing sorting results and comparisons.
TensorFlow/Keras: For building and training the ANN model.
Random: For generating test datasets.
Setup and Usage
Prerequisites
Ensure Python 3.8+ is installed along with the following libraries:

bash
Copy code
pip install numpy matplotlib tensorflow
Running the Project
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/sorting-optimization.git
cd sorting-optimization
Run the main script:

bash
Copy code
python main.py
View the results and visualizations generated during execution.

Project Structure
main.py: Main script to execute the project.
sorting_algorithms.py: Contains implementations of sorting algorithms.
optimization.py: Contains GA and PSO implementations.
ann_model.py: Contains ANN training and prediction logic.
visualization.py: Handles graphical representation of results.
README.md: Project documentation.
Results
The project identifies the best sorting algorithm for a given dataset using GA and PSO. It also predicts sorting times using the ANN model. Results include:

Sorting performance improvements with GA and PSO.
Predicted sorting times for unseen datasets.
Visual comparisons of original and optimized sorting.
Visualization
The project provides clear graphical representations of:

The original dataset.
Sorted datasets using GA and PSO-optimized algorithms.
Improvements in execution time for optimized sorting.
