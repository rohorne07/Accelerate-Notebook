# Accelerate-Notebook

Accelerating hit acquisition in drug screening, using a simulated docking molecule-target dataset as an example

Environment set up (note python 3.6 required for RDKit to run smoothly):

conda create -n “env_name” python=3.6 jupyter pandas seaborn matplotlib numpy

conda activate ‘env name’

conda install -c conda-forge rdkit

pip install sklearn

python -m ipykernel install --user --name “env_name” --display-name “env_name”

(Data unfortunately not included due to confidentiality)
