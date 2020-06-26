# AF-graph
Source code for the paper "Affinity Fusion Graph-based Framework for Natural Image Segmentation". The AF-Graph paper can be found [here](https://arxiv.org/abs/2006.13542).

AF-Graph is modified from [the offcial GL-Graph implementation](https://github.com/xiaofanglegoc/global-local-affinity-graph).


### Requirements
The code requires the version of Matlab2018a, Ubuntu 16.04.


### Data
The BSDS300 dataset and predata (extracted features) can be downloaded from [GL-Graph](https://github.com/xiaofanglegoc/global-local-affinity-graph) and place them in `BSD/` and `bsd_300_feat/` folder, respectively.


### Demo
Run the demo `demo_AF_Graph_BSD300.m`.


### Results of BSD300
The detailed results can be found in `evaluation.txt`.


### Other results

Coming soon!


### Citing
If you find this repository useful in your research, please consider citing:
```
@INPROCEEDINGS{AF-Graph,  
  author={Y. {Zhang} and M. {Liu} and J. {He} and F. {Pan} and Y. {Guo}},  
  booktitle={arXiv:2006.13542},   
  title={Affinity Fusion Graph-based Framework for Natural Image Segmentation},   
  year={2020}}
```
