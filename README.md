## Analysis of 500 Data Points from Statistics and Probability Course

![500 Data](https://github.com/user-attachments/assets/0811588f-09d0-4681-b568-d5e6340ccfe6)

This repository contains a Jupyter Notebook that details a statistical analysis performed on a dataset of 500 numerical values.  This project is based on an exercise from Dr. Hashem Hamedi Vafa's Statistics and Probability course and aims to address specific questions related to descriptive statistics and Gaussian distribution fitting as outlined in the exercise.

### Before Read Notebook (Persian version)
Download & install [Estedad](https://github.com/aminabedi68/Estedad/releases/download/7.3/Estedad-v7.3.zip) font for read better markdown

### Project Overview

**Objective:** To methodically address the questions posed in a statistical data analysis exercise using a dataset of 500 numbers. The exercise is divided into two main parts: analyzing the original dataset and then analyzing a linearly transformed version of the dataset.

**Dataset:** The dataset consists of 500 numerical values, originally sampled from a Gaussian distribution with a theoretical mean of 0 and standard deviation of 1, as specified in the exercise.

**Notebook Structure:** The Jupyter Notebook is structured to systematically answer each part of the exercise. The analysis is divided into two main sections, corresponding to the two questions in the exercise sheet:

**Part 1: Analysis of Original Data (Based on Exercise Question 1)**

This section of the notebook addresses the first question of the exercise, which involves a comprehensive descriptive statistical analysis of the original 500 data points.  The tasks performed are as follows:

1.  **Frequency Table Generation (Exercise 1a):**
    *   The notebook is designed to determine an appropriate number of class intervals (bins) for the data.
    *   It then constructs a frequency table that includes:
        *   Class intervals (bins) with connected classes.
        *   The center of each class interval.
        *   The frequency of data points within each class.
        *   Frequency density for each class.
        *   Cumulative frequency.
        *   Relative cumulative frequency (expressed as a percentage).

2.  **Calculation of Grouped Data Statistics (Exercise 1b):**
    *   Using the generated frequency table, the notebook calculates:
        *   The mean of the grouped data.
        *   The standard deviation of the grouped data.

3.  **Data Visualization (Exercise 1c):**
    *   The notebook generates graphical representations of the data distribution, specifically:
        *   A frequency histogram.
        *   A relative cumulative frequency plot (Ogive).

4.  **Quartile Determination (Exercise 1d):**
    *   The notebook calculates the quartiles of the data distribution:
        *   The first quartile (Q1).
        *   The second quartile (Q2 - Median).
        *   The third quartile (Q3).
    *   It also determines the Interquartile Range (IQR).

5.  **Robust Measures of Central Tendency (Exercise 1e):**
    *   To explore robust measures of central tendency, the notebook calculates:
        *   The 10% Trimmed Mean.
        *   The 10% Winsorized Mean.

6.  **Gaussian Distribution Fitting (Exercise 1f):**
    *   The notebook performs a Gaussian function fit to the frequency histogram. This involves:
        *   Using a suitable software function (like `curve_fit` from SciPy in Python) to fit a Gaussian curve to the histogram.
        *   Estimating the parameters of the fitted Gaussian function, specifically the mean and standard deviation.
        *   Visually presenting the Gaussian fit by overlaying the fitted curve on the histogram.
        *   (Implicitly, as part of assessing the fit) evaluating how well the fitted Gaussian parameters match expectations based on the theoretical properties of the original data distribution (Gaussian with mean 0 and standard deviation 1).

7.  **Normality Assessment:**
    *   Although not explicitly mentioned as a separate sub-question in Exercise 1, the notebook implicitly or explicitly assesses the normality of the original data to justify the Gaussian fitting process. This may involve using statistical tests for normality.

**Part 2: Linear Transformation and Re-analysis (Based on Exercise Question 2)**

This section addresses the second question in the exercise, which requires applying a linear transformation to the original dataset and then repeating a similar statistical analysis. The steps are:

1.  **Linear Transformation (Exercise 2a):**
    *   The notebook applies the specified linear transformation  $y = 5 - 3x$ to each value in the original dataset to create a new, transformed dataset.

2.  **Frequency Table for Transformed Data (Exercise 2b):**
    *   Similar to Part 1, step 1, a frequency table is generated for the transformed dataset, including:
        *   Class intervals, class centers, frequency, and relative frequency.

3.  **Grouped Data Statistics for Transformed Data (Exercise 2c):**
    *   The notebook recalculates the mean and standard deviation using the frequency table of the transformed data.
    *   It then evaluates whether the calculated statistics for the transformed data are consistent with what is theoretically expected after applying the linear transformation (i.e., how the mean and standard deviation should change based on the transformation formula).

4.  **Gaussian Fit for Transformed Data (Exercise 2d):**
    *   A Gaussian function is fitted to the frequency histogram of the transformed data, similar to Part 1, step 6.
    *   The notebook then assesses whether the results of the Gaussian fit for the transformed data are consistent with expectations, considering the effect of the linear transformation on the distribution.

**Key Libraries Used:**

*   `NumPy`: For numerical computations and array manipulations required for statistical calculations.
*   `pandas`: For efficient data manipulation and for creating DataFrames to organize and analyze frequency tables.
*   `matplotlib.pyplot`: For generating visualizations such as histograms and cumulative frequency plots.
*   `scipy.stats`: For utilizing statistical functions necessary for the analysis, such as those for trimmed mean, Winsorized mean, normality tests, and the normal distribution PDF.
*   `scipy.optimize.curve_fit`: For employing curve fitting techniques to fit the Gaussian function to the data histograms.

**Key Objectives Achieved:**

*   The notebook systematically addresses all parts of the statistical exercise, demonstrating a thorough understanding of descriptive statistics.
*   It provides practical implementation of statistical concepts using Python and relevant scientific libraries.
*   The project aims to show the impact of linear transformations on statistical properties of a dataset, by comparing the analysis before and after transformation.
*   Ultimately, this repository serves as a documented solution to the assigned exercise, showcasing the application of statistical methods in data analysis using computational tools.

