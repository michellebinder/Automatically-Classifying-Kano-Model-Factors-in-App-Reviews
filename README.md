This is the replication package that accompanies the paper

**Automatically Classifying Kano Model Factors in App Reviews** by
*Michelle Binder, Annika Vogt, Adrian Bajraktari, and Andreas Vogelsang*

https://link.springer.com/chapter/10.1007/978-3-031-29786-1_17

The package contains the following folders

- **code**: This folder contains Jupyter notebooks for all tested classifiers and the necessary preprocessing
- **datasets**: This folder contains the used dataset (Statik and Brunotte) including the Kano labels that we put manually. Additionally, we also provide the five downsampled datasets that we used to evaluate the classifiers.
- **results**: This folder contains a table with the collected results when the classifiers where trained on the Statik datasets and tested on the Brunotte dataset.

To run the code, you need Python3 including standard libraries (`pandas`, `numpy`, `matplotlib`, `sklearn`). In addition, you need to install the 'simpletransformers` library (e.g., via `pip`)
