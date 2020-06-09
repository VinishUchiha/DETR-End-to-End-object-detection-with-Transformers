# DETR: End-to-End-object-detection-with-Transformers

Two Weeks ago,**FacebookAI Research** published a paper named **End-to-End-object-detection-with-Transformers(DETR)**.Unlike traditional computer vision techniques, **DETR**(**DE**tection **TR**ansformer) approaches object detection as a direct set prediction problem. It consists of a set-based global loss, which forces unique predictions via bipartite matching, and a Transformer encoder-decoder architecture. Given a fixed small set of learned object queries, DETR reasons about the relations of the objects and the global image context to directly output the final set of predictions in parallel. Due to this parallel nature, DETR is very fast and efficient.</br>
DETR demonstrates accuracy and run-time performance on par with the well-established and highly-optimized Faster RCNN baseline on the challenging COCO object detection dataset. Moreover, DETR can be easily generalized to produce panoptic segmentation in a unified manner. We show that it significantly outperforms competitive baselines. Training code and pretrained models are available at https://github.com/facebookresearch/detr

DETR Paper: https://arxiv.org/abs/2005.12872


### Input and Inference:

![Input](https://github.com/VinishUchiha/DETR-End-to-End-object-detection-with-Transformers/blob/master/images/Airport.jpg)
![Inference](https://github.com/VinishUchiha/DETR-End-to-End-object-detection-with-Transformers/blob/master/images/predictions.png)
