# CS269-NLG

# Preparing Environment:

conda create -n pytorch1.5 python=3.6

source activate pytorch1.5

conda install pytorch=1.5 torch torchvision numpy transformers tqdm

conda install -c conda-forge ipython jupyter ipywidgets

python -m ipykernel install --user --name=pytorch1.5

# VQG Training using COCO data

Train VVQG using the below command:

 python main.py
 
 Please make sure that you download COCO dataset into the data folder before launching training. (See https://github.com/arjunakula/catr for more details on Data Preparation)

