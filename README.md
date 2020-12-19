# CS269-NLG

# Preparing Environment:

conda create -n pytorch1.5 python=3.6
source activate pytorch1.5
conda install pytorch=1.5 torch torchvision numpy transformers tqdm
conda install -c conda-forge ipython jupyter ipywidgets

python -m ipykernel install --user --name=pytorch1.5
