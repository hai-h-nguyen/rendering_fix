1. Install [anaconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)
2. Create and activate environment
```
conda create --name ex6 python=3.8.16
conda activate ex6
```
3. Install stuff (by default it install torch 1.10.1)
```
pip3 install -r requirements.txt
```
4. Test: Select ex6 as the environment to run the notebook (In VScode, when opening the notebook, there is a button on the right top corner to select which Python to run for the notebook). Finally, try to run the cell with button_callback to see if the four environments render when clicking a button