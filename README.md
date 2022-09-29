# A dataset for fire and smoke object detection
---
To advance object detection research in fire and smoke detection, we introduce a dataset called DFS (Dataset for Fire and Smoke detection), which is of high quality, constructed by collecting from real scenes and annotated by strict and reasonable rules. To reduce the possibility of erroneous judgments caused by objects that are similar to fires in color and brightness, apart from annotating ‘fire’ and ‘smoke’, we annotate these objects as a new class ‘other’. There are a total of 9462
images named by the fire size, which can benefit different detection tasks. Furthermore, by carrying out extensive and abundant experiments on Various object detection models, we provide a comprehensive benchmark on our dataset.

The download link of the DFS dataset is: BAIDUYUN： https://pan.baidu.com/s/1-kV1h78BwuNe-A86cDUuvQ, password：pnxx. OneDrive： https://1drv.ms/u/s!AnnO2n5F9u0IehApsqCBnnYvXvE?e=8nroFp 

Targets are labeled in VOC format.  

If you use this method in your research, please cite:
---

```
@article{wu2022dataset,  
  title={A dataset for fire and smoke object detection},  
  author={Wu, Siyuan and Zhang, Xinrong and Liu, Ruqi and Li, Binhai},  
  journal={Multimedia Tools and Applications},  
  pages={1--20},  
  year={2022},  
  publisher={Springer}  
}
```

```
@inproceedings{liu2021real,  
  title={Real-time fire detection network for intelligent surveillance systems},  
  author={Liu, Ruqi and Wu, Siyuan and Lu, Xiaoqiang},  
  booktitle={2nd International Conference on Computer Vision, Image, and Deep Learning},  
  volume={11911},  
  pages={225--238},  
  year={2021},  
  organization={SPIE}  
}
```


The Example of DFS.
---

The Fire Example：
![image](https://github.com/siyuanwu/DFS-FIRE-SMOKE-Dataset/blob/main/Figure/fire.png)

The Smoke Example：
![image](https://github.com/siyuanwu/DFS-FIRE-SMOKE-Dataset/blob/main/Figure/smoke.png)

The Other Example:
![image](https://github.com/siyuanwu/DFS-FIRE-SMOKE-Dataset/blob/main/Figure/other.png)

Comparison of the fire detection results using the yolov4 model trained on our DFS dataset and on
the other dataset.  
![image](https://github.com/siyuanwu/DFS-FIRE-SMOKE-Dataset/blob/main/Figure/comparison.png)
