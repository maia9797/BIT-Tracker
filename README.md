# BIT-Tracker
The official implementation for the **IEEE Transactions on Circuits and Systems for Video Technology** paper [_Bidirectional Interaction of CNN and Transformer Feature for Visual Tracking_](https://ieeexplore.ieee.org/document/10471584/authors#authors)


<p align="center">
  <img width="85%" src="https://github.com/maia9797/BIT-Tracker/tree/main/assets/Framework.png" alt="Framework"/>
</p>

## Abstract
Empowered by the sophisticated long-range dependency modeling ability of Transformer, tracking performance has seen a dynamic increase in recent years. Approaches in this vein leverage the Transformer feature to integrate the information of target and search regions while neglecting the superior local representation extracted by their CNN backbone. To address this, we introduce a BIdirectional inTeraction mechanism between CNN and Transformer features for visual tracking, termed BIT-Tracker, which admits a comprehensive fusion of local and global representations, and thus boosts tracking performance. The first ingredient of BIT-Tracker is an aggregation of multi-level Transformer features to achieve a better global modeling ability. In order to combine the merits of both local and global representations, our second ingredient performs a bi-directional interaction between CNN and Transformer features, where the interaction is achieved via either querying the CNN feature from the Transformer feature or querying the Transformer feature from the CNN feature. Afterwards, the outputs from both directions are fused to predict the temporal locations of targets. Extensive experiments demonstrate the effectiveness of the proposed feature aggregation and bi-directional interaction modules. Impressively, BIT-Tracker achieves leading performance on eight tracking benchmarks and outperforms SOTA results by salient margins.

| Tracker     | GOT-10K (AO) | LaSOT (AUC) | TrackingNet (AUC) | UAV123 (AUC) | NFS (AUC) |
|:-----------:|:------------:|:-----------:|:-----------------:|:------------:|:---------:|
| BIT-Tracker | 73.1         | 68.6        | 83.0              | 70.9         | 67.8      |

[[Raw Results](https://drive.google.com/drive/folders/1V56yjldB6EWvQt-emmXnZa_1whWymid4?usp=sharing)]

## Good performance-speed trade-off
<p align="center">
  <img width="70%" src="https://github.com/maia9797/BIT-Tracker/tree/main/assets/speed_vs_performance.png" alt="speed_vs_performance"/>
</p>

## Models
[[Models](https://drive.google.com/drive/folders/1Z_zBa-pjzlBUdr0nmbuaH1p54zdAYg40?usp=sharing)]

## Citation
If our work is useful for your research, please consider citing:

```Bibtex
@ARTICLE{BIT2024sun,
  author={Sun, Baozhen and Wang, Zhenhua and Wang, Shilei and Cheng, Yongkang and Ning, Jifeng},
  journal={IEEE Transactions on Circuits and Systems for Video Technology}, 
  title={Bidirectional Interaction of CNN and Transformer Feature for Visual Tracking}, 
  year={2024},
  volume={34},
  number={8},
  pages={7259-7271}}
```
