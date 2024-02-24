# Central Limit Theorems via Analytic Combinatorics in Several Variables

This repository contains two Sage Jupyter notebooks for [*Central Limit Theorems via Analytic Combinatorics in Several Variables*](https://arxiv.org/abs/2211.15492) by Stephen Melczer and Tiadora Ruza. 

The first notebook contains code to take a rational function, check whether it satisfies the conditions of Proposition 13 in the paper, and (if so) return the local central limit theorem satisfied by its coefficients. To perform the necessary computations, the notebook requires the [sage_acvsv package](https://github.com/ACSVmath/sage_acsv). The ability to detect and prove local central limit theorems will eventually be merged into the sage_acsv package.

The second notebook contains code to compute a local central limit theorem for a rational function known to satisfy the conditions of Theorem 20 in the paper (which is a stronger requirement). This notebook does not require the sage_acsv package, and also contains some computations appearing in the proof of Theorem 20.