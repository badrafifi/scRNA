wget https://ftp.ncbi.nlm.nih.gov/geo/series/GSE235nnn/GSE235063/suppl/GSE235063_RAW.tar


conda create -n scRNA python=3.9
conda env list

conda activate scRNA

pip install notebook scanpy doubletdetection
