# Simple and Deep Graph Convolutional Networks
This repository contains a PyTorch implementation of "Simple and Deep Graph Convolutional Networks".(https://arxiv.org/abs/2007.02133)
## Dependencies
- CUDA 10.1
- python 3.6.9
- pytorch 1.3.1
- networkx 2.1
- scikit-learn

## Datasets

The `data` folder contains three benchmark datasets(Cora, Citeseer, Pubmed), and the `newdata` folder contains four datasets(Chameleon, Cornell, Texas, Wisconsin) from [Geom-GCN](https://github.com/graphdml-uiuc-jlu/geom-gcn). We use the same semi-supervised setting as [GCN](https://github.com/tkipf/gcn) and the same full-supervised setting as Geom-GCN. PPI can be downloaded from [GraphSAGE](http://snap.stanford.edu/graphsage/).

## Results
請見GCNII與本論文

```
## 補充
```
輸入:見資料夾DATA與SPILTS
輸出:使用ALLGCNII或ALLMSSOGCNII輸出
請在kaggle之環境下開啟GPU100下執行以下檔案
各檔案功能
ALLGCNII:復現GCNII結果 除了將模型改為可調整超參數與模型架構外 僅修復BUG 表現可對照原論文
ALLMSSOGCNII:MSSOGCNII結果 表現可參照本研究論文
搜尋:可使用MSSO搜索超參數與模型架構 僅以CORA為例 剩餘資料集以此推類
其餘檔案功能同原論文之解釋 不多贅述
```
## Citation
```
@article{chenWHDL2020gcnii,
  title = {Simple and Deep Graph Convolutional Networks},
  author = {Ming Chen, Zhewei Wei and Zengfeng Huang, Bolin Ding and Yaliang Li},
  year = {2020},
  booktitle = {Proceedings of the 37th International Conference on Machine Learning},
}
```
