Name: Dhanush Patel
SID: 3033247258
Reproduction instructions:
- Make sure the required libraries mentioned in problem #1 are installed. I did so in a conda env.
- In the env, run "jupyter lab" or "jupyter notebook" in the same folder as the .ipynb file. Either command should work, but I did the former. Make sure to have the .ipynb file in the same folder as the "check.py" and "save_csv.py"; both of those python files are in the folder enclosing the "data" folder (another way to phrase that: they're not inside the "data" folder).
- If you want to test all cells, it is important to run them in order (easy way is to just run all cells after opening the notebook) since some cells have the same variable names as other cells and so running cells out of order may result in errors and/or incorrect results. Almost all cells run in a reasonable amount of time, but I believe a cell I've written for hyperparameter tuning in problem #6 for CIFAR-10 takes longer than average.