# mlops_basic_ml_practise-1

# conda environment creation command

conda env create -f environment.yaml

# conda environment updation command

conda env update --file environment.yml --prune

# Sometimes kernel issues may come while running the jupyter notebook
# in VSCode. Install python & jupyter extensions and include ipykernel in 
# the environment.yaml

# command to register the kernel name.
# when you select kernel --> select jupyter kernel 
python -m ipykernel install --user --name mlops_ml_practise_1_env --display-name "Python (mlops_ml_practise_1_env)"

