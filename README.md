# Co-Compression via Superior Gene for Remote Sensing Scene Classification
**Abstract：** <br />
Convolutional neural networks (CNNs) have been successfully employed in remote sensing image classification because of their robust feature representation for different visual tasks and powerful graphics processing units (GPUs). The attendant problem is that high computational cost and high memory footprint hindering the application of CNNs for remote sensing applications in resource- and time-sensitive situations. Based on practical deployment requirements, we pioneer a pruning-quantization joint learning model compression method for remote sensing image classification, called co-compression via superior gene (CC-SG). An enhanced evolution algorithm (EEA) is adopted as the agent to search a “superior gene,” and immediately following, a director receives the “superior gene” and gives a compression mask and a resource constraint feedback to the agent. The network is eventually compressed and fine-tuned according to the optimal compression mask. Specifically, we introduce gene age and progressive shrinkage mutation rate to EEA and design a fitness function that balances accuracy and resource constraints. As validated using the UC Merced land-use and NWPU-RESISC45 datasets, the proposed CC-SG demonstrated superiority over other compared model compression approaches. For example, CC-SG attained substantial bit operations (BOPs) compression ratio of 40.04 with 0.956% accuracy increase for VGG-16 on UC Merced land-use dataset and 40.00 with 0.203% accuracy increase for ResNet-56 on NWPU-RESISC45 dataset. The code is available at https://github.com/fanxxxxyi/CC-SG . <br />
**Code & Model:** https://github.com/fanxxxxyi/CC-SG <br />
**Paper:** https://doi.org/10.1109/TGRS.2023.3247872
<br />
If our code is helpful to you, please cite:
```
@ARTICLE{10050000,
  author={Xie, Weiying and Fan, Xiaoyi and Zhang, Xin and Li, Yunsong and Sheng, Min and Fang, Leyuan},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Co-Compression via Superior Gene for Remote Sensing Scene Classification}, 
  year={2023},
  volume={61},
  number={},
  pages={1-12},
  doi={10.1109/TGRS.2023.3247872}}

```
