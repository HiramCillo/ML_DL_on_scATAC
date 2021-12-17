# Description of this portfolio

This portfolio contains my notebooks about machine and deep learning algorithms applied on **single-cell ATAC-seq data**. There are described below: 

## [scATAC-seq 🧬: Feature Importance with TabNet](notebooks/scatac-seq-feature-importance-with-tabnet.ipynb) (see it in action at [Kaggle](https://www.kaggle.com/hiramcho/scatac-seq-feature-importance-with-tabnet))
In this notebook, i used **TabNet**, a kind of transformer useful for tabular data. As many now, **expressión data** is just a *matrix*. This matrix is contained on my `adata` object, `adata.X`. In resume, i used the mentioned matrix and `adata.obs["nucleosome_signal"]` as my labels, i split it, trained my model and calculate **feature importance** as you can see below:  
![feature_imp_tab](img/feat_imp_tb_atac.png)  