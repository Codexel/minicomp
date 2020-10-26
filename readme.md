## Rossman Mini-Competition

This is the winning solution from a Mini-Competition at Data Science Retreat in Berlin. The goal is to predict future sales in Rossman stores across Europe. The data - originally from a Kaggle challenge - has been manipulated using the data.py file (introducing NaNs etc) to increase the difficulty. 

The competition was held with limited time and the notebooks are left in their original state as they were at the competition's submission deadline. 

The solution was awarded first place for an achieved RMSPE of 19%.

Instructions:
1. Clone this repo
2. Set up a new conda environment using environment.yml: 
`conda env create -f environment.yml`
3. Activate the conda environment you just created:
`conda activate minicomp`
4. Launch Jupyter Notebook and open test_notebook.ipynb
5. Run all cells in test_notebook.ipynb to use our model and get the final score
6. If you want to see how the training went, open the train_notebook. If you want to see how the cleaning went, open the clean_notebook. 