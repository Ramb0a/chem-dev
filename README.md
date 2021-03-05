# chem-dev

start container -p 8888:8888

source activate my-rdkit-env

conda install -c conda-forge --file requirements.txt

jupyter notebook --port=8888 --no-browser --ip=0.0.0.0 --allow-root
