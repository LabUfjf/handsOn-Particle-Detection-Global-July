# Hands-on to Solve Particle Detection Tracks Using a High-Resolution Camera

Welcome to the Hands-on to Solve Particle Detection Tracks Using a High-Resolution Camera repository! This repository contains the materials and instructions for a comprehensive hands-on session on signal processing using Python and Jupyter Notebooks. The hands-on is designed to provide practical experience in image data analysis, pre-processing techniques, clustering, feature calculation, and data visualization.

## Hands-On Breakdown

The hands-on session is divided into five lectures, each covering a specific topic:

1. Lecture 1: Opening and Viewing Image Data
   - Introduction to opening and exploring a dataset containing images.
   - Instructions on how to view individual images and groups of ten images.

2. Lecture 2: Pre-processing Techniques for Noise Reduction
   - Explanation of pre-processing techniques to clean electronic noise from images.
   - Demonstration of at least two techniques and a comparison of their effectiveness.

3. Lecture 3: Clustering Techniques for Grouping Information
   - Introduction to clustering techniques for grouping relevant information in images.
   - Comparison of different clustering approaches and their performance evaluation.

4. Lecture 4: Feature Calculation based on Clusterization Output
   - Instructions on utilizing the output of clustering to calculate relevant features.
   - Demonstration of feature extraction from the clustered data.

5. Lecture 5: Data Visualization of Created Features
   - Guidance on creating data visualization plots to visualize the calculated features.
   - Showcase of visually informative representations of the results.

## Repository Structure

The repository is structured as follows:

- `lecture1/`: Contains the Jupyter Notebook for Lecture 1.
  - `handson_1.ipynb`: Includes imported libraries and useful code.
  - `example.ipynb`: Provides additional examples for reference.

- `lecture2/`: Contains the Jupyter Notebook for Lecture 2.
  - `handson_2.ipynb`: Includes imported libraries and useful code.
  - `example.ipynb`: Provides additional examples for reference.

- `lecture3/`: Contains the Jupyter Notebook for Lecture 3.
  - `handson_3.ipynb`: Includes imported libraries and useful code.
  - `example.ipynb`: Provides additional examples for reference.

- `lecture4/`: Contains the Jupyter Notebook for Lecture 4.
  - `handson_4.ipynb`: Includes imported libraries and useful code.
  - `example.ipynb`: Provides additional examples for reference.

- `lecture5/`: Contains the Jupyter Notebook for Lecture 5.
  - `handson_5.ipynb`: Includes imported libraries and useful code.
  - `example.ipynb`: Provides additional examples for reference.

- `dataset/`: Directory for relevant datasets and images.
  - `/signal`: Folder containing signal image files.
  - `/background`: Folder containing background image files.
  - `/calibration`: Folder containing calibration image files.


## Getting Started

To use the repository, you have two options: running the code on Google Colab or setting it up on your local machine. Follow the instructions below based on your preferred environment.

### Google Colab

1. Open the repository in your web browser by clicking on the repository link: [Hands-on Particle Detection Global July](https://github.com/LabUfjf/handsOn-Particle-Detection-Global-July).

2. Navigate to the desired lecture folder, such as `lecture1`.

3. Click on the `code.ipynb` file to open it in Google Colab.

4. Once the notebook opens, click on the "Open in Colab" button at the top of the page. This will launch the notebook in Google Colab.

5. Follow the instructions and execute the code cells in the notebook. Modify the code as instructed during the hands-on session.

### Local Machine Setup

#### Prerequisites

- Python 3.x installed on your local machine. If you don't have Python installed, you can download it from the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/).

#### Instructions

1. Clone the repository to your local machine using Git or download it as a ZIP file and extract it to a desired location.

   ```shell
   git clone https://github.com/your-username/your-repository.git

2. Open a command line or terminal window.

3. Navigate to the lecture folder you want to work on, for example, lecture1.
   
   ```shell
    cd your-repository/lecture1`

4. Create a virtual environment (optional but recommended) to isolate the project dependencies.

   For Windows: 
      ```
        python -m venv venv
        venv\Scripts\activate
      ```

   For macOS and Linux:

      ```
         python3 -m venv venv
         source venv/bin/activate
      ```
5. Install the required dependencies by executing the following command:
   ```
      pip install -r requirements.txt
   ```
6. Launch Jupyter Notebook to run the code:
   ```
      jupyter notebook
   ```

8. In your web browser, Jupyter Notebook will open automatically. Click on the handson_1.ipynb notebook to open it.

9. Follow the instructions and execute the code cells in the notebook. Modify the code as instructed during the hands-on session.

## Requirements

Make sure you have the following dependencies installed:

- Python (version X.X.X)
- Jupyter Notebook (version X.X.X)
- Additional libraries specified in the notebook (if any)

Please refer to the official documentation of each library or framework for installation instructions.

## Feedback and Contributions

We appreciate your feedback on the hands-on session and welcome any contributions that can enhance the learning experience. If you encounter any issues, have suggestions, or would like to contribute, please open an issue or submit a pull request to this repository.

## License

This hands-on session is released under the [MIT License](LICENSE).

Happy learning and exploring the fascinating world of signal processing and electrical engineering!

## Useful bibliografy

- González, R.C., Woods, R.E., & Eddins, S.L. (2008). Digital Image Processing Using MATLAB. Gatesmark Publishing.
- Oppenheim, A.V., & Schafer, R.W. (2010). Discrete-Time Signal Processing. Prentice Hall.
- Proakis, J.G., & Manolakis, D.G. (2006). Digital Signal Processing: Principles, Algorithms, and Applications. Prentice Hall.
- Haykin, S., & Van Veen, B. (2002). Signals and Systems. Wiley.
- Quatieri, T.F. (2002). Discrete-Time Speech Signal Processing: Principles and Practice. Prentice Hall.
- Vaidyanathan, P.P. (2011). Multirate Systems and Filter Banks. Prentice Hall.
- Scharf, L.L. (1991). Statistical Signal Processing: Detection, Estimation, and Time Series Analysis. Addison-Wesley.
- Stoica, P., & Moses, R.L. (2005). Introduction to Spectral Analysis. Prentice Hall.
- Oppenheim, A.V., & Schafer, R.W. (2015). Digital Signal Processing using MATLAB. Cengage Learning.
- Mitra, S.K. (2010). Digital Signal Processing: A Computer-Based Approach. McGraw-Hill.
- Proakis, J.G., & Ingle, V.K. (2013). Digital Signal Processing: Principles, Algorithms, and Applications. Pearson.
- Lyons, R.G. (2010). Understanding Digital Signal Processing. Pearson.
- Marple Jr., S.L. (1987). Digital Spectral Analysis with Applications. Prentice Hall.
- Poularikos, A., & Gaydecki, P. (2012). Applied Signal Processing: Concepts, Circuits, and Systems. Wiley.

