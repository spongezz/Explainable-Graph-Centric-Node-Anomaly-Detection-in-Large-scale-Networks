Each dataset can be run by the following commands


python run.py --psi 2 --dataset cora --h 1 --lamda 0.0625
python run.py --psi 2 --dataset citeseer --h 1 --lamda 0.125
python run.py --psi 2 --dataset pubmed --h 1 --lamda 0.0625
python run.py --psi 2 --dataset BlogCatalog --h 1 --lamda 0.003125
python run.py --psi 2 --dataset Flickr --h 1 --lamda 0.003125
python run.py --psi 2 --dataset ACM --h 1 --lamda 0.0625

python run.py --psi 2 --dataset lattice --h 1 --lamda 0.0
python run.py --psi 8 --dataset lattice_s --h 1 --lamda 0.003125
python run.py --psi 4 --dataset RGG_1 --h 2 --lamda 0.0
python run.py --psi 8 --dataset RGG_2 --h 1 --lamda 0.0625
python run.py --psi 2 --dataset SBM_c --h 4 --lamda 0.0625
python run.py --psi 2 --dataset SBM_d --h 4 --lamda 0.0625
python run.py --psi 2 --dataset SBM_str --h 1 --lamda 0.25
python run.py --psi 2 --dataset watts_strogatz --h 1 --lamda 0.0

python WL_cen_un_newadj.py --psi 2 --dataset citeseer --h 1 --lamda 0.125
python WL_cen_un_newadj.py --psi 2 --dataset pubmed --h 1 --lamda 0.0625
python WL_cen_un_newadj.py --psi 2 --dataset BlogCatalog --h 1 --lamda 0.003125
python WL_cen_un_newadj.py --psi 2 --dataset Flickr --h 1 --lamda 0.003125
python WL_cen_un_newadj.py --psi 2 --dataset ACM --h 1 --lamda 0.0625