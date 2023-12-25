Overview
This homework assignment focuses on applying digital image processing techniques, specifically Fourier Transform (FFT) and Wiener filtering, to process and restore images. It involves two main problems:

Problem 1: FFT
Task: Perform various operations using the Discrete Fourier Transform (DFT) of an image.
Key Steps:
Compute the DFT of an image.
Create f1(x, y) by setting the magnitude to 1 for all frequencies in the DFT and computing the inverse DFT.
Create f2(x, y) by setting the phase to 0 for all frequencies in the DFT and computing the inverse DFT.
Apply filters h1 and h2 to a noisy image and display results in both the frequency and spatial domain.
Experiment with different levels of noise and compare the results.

Problem 2: Wiener Filter
Task: Design a Wiener filter to restore an image that is degraded by motion blur and additive Gaussian noise.
Approach:
Use trial-and-error to find the best filter parameters.
Experiment with different kernel sizes and noise levels.
Evaluate using the Mean Squared Error (MSE) metric.
Deliverables:
Expression and parameters of the best Wiener filter.
Display of the best restoration result.

Code Structure
code/: Directory containing the code files for the assignment.
HW2.py: Code for Problem 1 and 2 task
HW2.ipynb: Code for Problem 1 and 2 task 

Report
report.pdf: A detailed report of the assignment, containing:
Overview of the problems.
Details of the approach and algorithms used.
Results and any observations or conclusions drawn from the assignment.