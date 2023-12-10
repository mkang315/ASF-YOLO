# Official ASF-YOLO
This is the source code for the paper, "ASF-YOLO: A Novel YOLO Model with Attentional Scale Sequence Fusion for Cell Instance Segmentation", of which I am the first author.

## Model
The model configuration (i.e., network construction) file is asf-yolo.yaml in the directory [./models/segment](https://github.com/mkang315/ASF-YOLO/blob/main/models/segment).

#### Training

The hyperparameter setting file is hyp.scratch-low.yaml in the directory [./data/hyps/](https://github.com/mkang315/ASF-YOLO/blob/main/data/hyps).

###### Training CLI
```
python segment/train.py
```

#### Testing CLI

```
python segment/predict.py
```

## Evaluation
We trained and evaluated ASF-YOLO on the two [datasets](https://github.com/mkang315/ASF-YOLO/tree/main/datasets): [2018 Data Science Bowl (DSB2018)](https://kaggle.com/competitions/data-science-bowl-2018) from Kaggle and [Breast Cancer Cell (BCC) dataset](https://bioimage.ucsb.edu/research/bio-segmentation) from the Center for Bio-Image Informatics, University of California, Santa Barbara (UCSB CBI).

## Suggested Citation
Our manuscript has been uploaded on [arXiv](https://arxiv.org/abs/2312.00000). Please cite our paper if you use code from this repository:
> Plain Text

- *IEEE* Style</br>
M. Kang, C.-M. Ting, F. F. Ting, and R. C.-W. Phan, "Asf-yolo: A novel YOLO model with attentional scale sequence fusion for cell instance segmentation," arXiv:2312.00000 [cs.CV], Dec. 2023.</br>

- *Nature* Style</br>
Kang, M., Ting, C.-M., Ting, F. F. & Phan, R. C.-W. ASF-YOLO: a novel YOLO model with attentional scale sequence fusion for cell instance segmentation. Preprint at https://arxiv.org/abs/2312.00000 (2023).</br>

- *Springer* Style</br>
Kang, M., Ting, C.-M., Ting, F. F., Phan, R.C.-W.: ASF-YOLO: a novel YOLO model with attentional scale sequence fusion for cell instance segmentation. arXiv preprint [arXiv:2312.00000](https://arxiv.org/abs/2312.00000) (2023)</br>

## License
ASF-YOLO is released under the GNU Affero General Public License v3.0 (AGPL-3.0). Please see the [LICENSE](https://github.com/mkang315/ASF-YOLO/blob/main/LICENSE) file for more information.

## Copyright Notice
Many utility codes of our project base on the codes of [Ultralytics YOLOv5](https://github.com/ultralytics/yolov5), and [EIoU](https://github.com/arojsubedi/Focal-EIoU) repositories.
