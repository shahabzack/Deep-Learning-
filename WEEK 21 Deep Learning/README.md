  How to create a enivornment in step by step 
  
  1 - conda create -n deep python=3.8
  2 - conda activate deep
  3 - conda install numpy
      conda install pandas
      conda install scikit-learn
      conda install matplotlib
      conda install seaborn
      conda install tensorflow
  
  To show in Jupternotebbok new env
- conda install ipykernel  ( if alredy installed then skip)
- python -m ipykernel install --user --name=deep --display-name="Deep Learning Environment"

then run it.


Version of Installed Libraries 

- NumPy version: 1.23.5
- Pandas version: 2.0.3
- scikit-learn version: 1.3.0
- Matplotlib version: 3.7.2
- Seaborn version: 0.13.2
- TensorFlow version: 2.3.0