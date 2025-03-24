## Analysis of 500 Data Points from Statistics and Probability Course

This repository contains a jupyter notebook file that performs a comprehensive statistical analysis on a dataset of 500 numerical values. The analysis is based on exercises from Dr. Hashem Hamedi Vafa's statistics and probability course and covers key concepts in descriptive statistics and data distribution fitting.

### Before Read Notebook (Persian version)
Download & install [Estedad](https://github.com/aminabedi68/Estedad/releases/download/7.3/Estedad-v7.3.zip) font for read better markdown

**Key Operations Performed:**

*   **Data Exploration and Classification:**
    *   Data loading and unique value extraction.
    *   Frequency distribution analysis.
    *   Visualization of data distribution using scatter plots.

*   **Descriptive Statistics:**
    *   **Frequency Tables:** Creation of frequency tables including:
        *   Class intervals (bins) using automatic bin selection.
        *   Bin centers.
        *   Frequency density.
        *   Cumulative frequency.
        *   Relative cumulative frequency.
    *   **Measures of Central Tendency and Dispersion:**
        *   Calculation of mean and standard deviation for grouped data.
        *   Quartiles (Q1, Q2, Q3) and Interquartile Range (IQR).
        *   Trimmed mean and Winsorized mean for robust central tendency estimation.

*   **Data Visualization:**
    *   **Histograms:** Generation of frequency histograms and relative cumulative frequency histograms.
    *   **Relative Cumulative Frequency Plot:** Visualization of cumulative frequency distribution.

*   **Gaussian Distribution Fitting:**
    *   **Fitting Gaussian Function:** Applying the `curve_fit` function from `SciPy` to fit a Gaussian function to the frequency distribution histogram.
    *   **Parameter Estimation:** Estimation of mean and standard deviation from the fitted Gaussian function.
    *   **Visualization of Gaussian Fit:** Overlaying the fitted Gaussian curve on the histogram and highlighting quartile ranges under the curve.
    *   **Comparison with Normal PDF:** Plotting the Probability Density Function (PDF) of the standard normal distribution for comparison.

*   **Linear Transformation and Analysis:**
    *   **Applying Linear Transformation:** Transformation of the original dataset using the linear equation  $y = 5 - 3x$.
    *   **Repeating Descriptive Analysis:** Re-calculation of frequency tables, mean, standard deviation, and Gaussian fitting for the transformed data to observe the effect of linear transformation on statistical properties.


**Libraries Used:**

*   `NumPy`: For numerical operations and array manipulation.
*   `pandas`: For data manipulation and creating DataFrames for frequency tables.
*   `matplotlib.pyplot`: For creating static, interactive, and animated visualizations in Python.
*   `scipy.stats`: For statistical functions, including trimmed mean, Winsorized mean, and normal distribution PDF.
*   `scipy.optimize.curve_fit`: For fitting a Gaussian function to the data.

**Key Findings and Observations (Optional):**

*(You can add a brief section here summarizing your key findings, for example:)*

*   The original data distribution and its statistical properties.
*   The parameters of the Gaussian function fitted to the data.
*   The impact of the linear transformation on the mean, standard deviation, and overall distribution of the data.
*   Consistency of the estimated mean and standard deviation with expected values after linear transformation.

**Course:**

Statistics and Probability Course - Dr. Hashem Hamedi Vafa

---


![500 Data](https://github.com/user-attachments/assets/0811588f-09d0-4681-b568-d5e6340ccfe6)
