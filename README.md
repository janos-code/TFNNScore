# TFNNScore
Keras implementation of NNScore described in "Soft Computing Tools for Virtual Drug Discovery" by Daniel M Hagan and Martin T Hagan

tfnnscore2layer.py contains the program and tfdata.mat has the preprocessed data. All you need to do to run the program is put tfnnscore2layer.py and tfdata.mat in the same folder and then in the command line "python3 tfnnscore2layer.py". The output files showing results will be saved in the same directory. Training takes 1-2 hours on a VM with 8 vCPU's, 30gb memory and 1 NVIDIA Tesla P100 GPU.
