# A dataset for fire and smoke object detection
---
To advance object detection research in fire and smoke detection, we introduce a dataset called DFS (Dataset for Fire and Smoke detection), which is of high quality, constructed by collecting from real scenes and annotated by strict and reasonable rules. To reduce the possibility of erroneous judgments caused by objects that are similar to fires in color and brightness, apart from annotating ‘fire’ and ‘smoke’, we annotate these objects as a new class ‘other’. There are a total of 9462
images named by the fire size, which can benefit different detection tasks. Furthermore, by carrying out extensive and abundant experiments on Various object detection models, we provide a comprehensive benchmark on our dataset.

The download link of the DFS dataset is: https://pan.baidu.com/s/1k0fwF84mjGGUXnunqhhcRw, password：menk. Targets are labeled in VOC format.  

If you use this method in your research, please cite:
---

```
@article{oberweger2015hands,

  title={Hands Deep in Deep Learning for Hand Pose Estimation},

  author={Oberweger, Markus and Wohlhart, Paul and Lepetit, Vincent},

  journal={arXiv preprint arXiv:1502.06807},

  year={2015}
  
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
the dataset posted by Lei.  
![image](https://github.com/siyuanwu/DFS-FIRE-SMOKE-Dataset/blob/main/Figure/comparison.png)