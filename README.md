# entropy_dnn
Code for project on relative entropy in deep neural networks. Files included:

* `Gaussian_Feedforward.ipynb` -- jupyter notebook that creates and trains feedforward random networks used in the analysis; data written in HDF5 format.

* `Gaussian_Feedforward_Analysis.ipynb` -- jupyter notebook that reads HDF5 files created by `Gaussian_Feedforward.ipynb` and performs analysis (e.g., computes correlation length, generates plots).

* `Relative_Entropy.ipynb` -- jupyter notebook that reads HDF5 files created by `Gaussian_Feedforward.ipynb` and computes the relative entropy or Kullback-Leibler (KL) divergence as a function of depth.

It is recommended to open the `.ipynb` files with jupyter so that LaTeX expressions in markdown cells are rendered correctly. 
