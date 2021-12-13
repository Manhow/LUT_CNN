To run the program google colab or conda must be used to open a jupyter notebook file.

How to run:
1. Open 'ADAML.ipynb' in jupyter notebook. 
2. Make sure the environment contains the frameworks mentioned in the section 'Adjust workspace'
3. Edit line 'filenames, labels = get_filenames("C:/Users/misha/Desktop/sample_project_1/data")'
You should indicate the path where are 112 folder with corresponding images.
4. Change logdir path in 'create_tensorboard_callback()' for TensorBoard or comment TensorBoard
5. Change modeldir path in `save_model` if you want to train the model. Also if you want to train, remove WoodClassification.h5
6. Run all lines and see 'model.evaluate(valid_data)'
