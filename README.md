# Diabetes-Predictive-Model
A machine learning model to predict if a patient has diabetes.

To run this project do the following:
1. Ensure that MiniConda is installed on your machine: https://docs.conda.io/projects/miniconda/en/latest/
2. Open Anaconda Prompt (Miniconda3) terminal that was downloaded.
3. In the terminal change directories to the folder with the downloaded Jupyter Notebook and data for this project.
4. Create a Conda environement containing: Pandas, MatPlotLib, NumPy, Scikit-Learn, Jupyter (you can name the environment whatever you want after the -n… I named mine ml_env)
	conda create -n ml_env python numpy pandas matplotlib jupyter scikit-learn
5. Activate the environment:
	conda activate ml_env
6. Open Jupyter Notebook:
	jupyter notebook
7. You should now be at the home dashboard and if in the correct directory should see my .ipynb file, click on it to open it and scroll all the way to the bottom.
8. Click on the cell that has the comment “Use this for making predictions” (the last cell)
9. Edit the variables and click run or cntrl + enter to run the cell it should output the prediction. There is an example prediction right above.

Credit for the dataset goes to:
Mohammed Mustafa which can be found here: https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset
