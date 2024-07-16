# Solving the Travelling Salesman Problem using Self-Organizing Maps
This project demonstrates how to solve the Travelling Salesman Problem (TSP) using Self-Organizing Maps (SOMs). The repository includes various datasets, scripts for running the SOM algorithm, and visualizations of the results.

# Project Structure
## Assets
* **TSP Datasets:**
  * ar9152.tsp
  * fi10639.tsp
  * it16862.tsp
  * ja9847.tsp
  * qa194.tsp
  * uy734.tsp
  
## Diagrams
* Sequential images (00000.png to 24000.png) showing the SOM training process.
* final.png: Final route found by the SOM.
* route.png: Visualization of the route.
* uruguay.gif: Animated visualization of the SOM training process.

## Report
* **Images:**
  * finnish_som.png
  * italy.png
  * uruguay.png
* **Reports:**
  * report.org
  * report.pdf
* **Slides:**
  * slides.org
  * slides.pdf
    
## Source Code
* **distance.py:** Functions for calculating distances.
* **io_helper.py:** Helper functions for input/output operations.
* **main.py:** Main script to run the SOM algorithm.
* **neuron.py:** Definition and management of neurons in the SOM.
* **plot.py:** Functions for plotting the results.

## Documentation
* **README.md:** Project documentation (this file).
* **requirements.txt:** Required Python libraries.
  
# Getting Started
## Prerequisites
* Python 3.6 or higher
* Required Python libraries (listed in requirements.txt)
  
# Installation
1. Clone the repository:
`git clone https://github.com/yourusername/tsp-som.git`
`cd tsp-som`
2. Install the required libraries:
`pip install -r requirements.txt`

## Usage
1. Running the SOM Algorithm:
* Execute main.py to run the Self-Organizing Maps algorithm on the provided TSP datasets.
`python src/main.py`

2. Visualizing Results:
* View the generated diagrams in the diagrams folder to see the progression of the SOM training.
* Check the final.png and route.png for the final route visualizations.
* Open uruguay.gif to see an animated visualization of the SOM training process.
  
# Reports and Presentations
* Detailed reports are available in report.pdf and report.org.
* Presentation slides can be found in slides.pdf and slides.org.
