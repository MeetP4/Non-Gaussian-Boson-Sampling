# Non-Gaussian Boson Sampling
This Python program allows you to study the interference patterns of a family of non-Gaussian states of light in arbitrary optical networks.

To Run: </br>

In order to obtain correlation analysis results as well as tabulated probabilities, set input states in the file</br>

states = (np.array([1,1]),np.array([1,1])) interfering in an optical network </br>
It means 2 input states of light  $\frac{1}{\sqrt{2}}\left(\ket{0} + \ket{1}\right)$ </br>

states = (np.array([1,1]),np.array([1,1]), np.array([1,1]))  </br>
It means 3 input states of light  $\frac{1}{\sqrt{2}}\left(\ket{0} + \ket{1}\right)$ interfering in an optical network</br>

Run: </br>
python photon_correlation.py </br>


Master's Thesis </br>
Czech Technical University Prague </br>
Author: Meet Rajkumar Panchal </br>
