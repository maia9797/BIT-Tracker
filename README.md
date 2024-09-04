# BIT-Tracker
The official implementation for the **IEEE Transactions on Circuits and Systems for Video Technology** paper [_Bidirectional Interaction of CNN and Transformer Feature for Visual Tracking_](https://ieeexplore.ieee.org/document/10471584/authors#authors)

[[Models](https://drive.google.com/drive/folders/1Z_zBa-pjzlBUdr0nmbuaH1p54zdAYg40?usp=sharing)][[Raw Results](https://drive.google.com/drive/folders/1V56yjldB6EWvQt-emmXnZa_1whWymid4?usp=sharing)]

<p align="center">
  <img width="85%" src="https://github.com/maia9797/BIT-Tracker/tree/main/assets/Framework.png" alt="Framework"/>
</p>

## Highlights

### ⭐: New Tracking Framework
BIT-Tracker proposed a new tracking framework, enabling the bidirectional interaction between CNN and Transformer features to effectively capture both local and global information in a comprehensive fashion.
Empirically, the proposed BIT-Tracker performs significantly better than the SOTA approaches and achieves leading performance on popular benchmarks.

| Tracker     | GOT-10K (AO) | LaSOT (AUC) | TrackingNet (AUC) | UAV123 (AUC) | NFS (AUC) |
|:-----------:|:------------:|:-----------:|:-----------------:|:------------:|:---------:|
| BIT-Tracker | 73.1         | 68.6        | 83.0              | 70.9         | 67.8      |

### ⭐: Good performance-speed trade-off
<p align="center">
  <img width="70%" src="https://github.com/maia9797/BIT-Tracker/tree/main/assets/speed_vs_performance.png" alt="speed_vs_performance"/>
</p>

## Code
The code is still being sorted out.

## Citation
If our work is useful for your research, please consider citing:

```Bibtex
@article{sun2024bidirectional,
  title={Bidirectional Interaction of CNN and Transformer Feature for Visual Tracking},
  author={Sun, Baozhen and Wang, Zhenhua and Wang, Shilei and Cheng, Yongkang and Ning, Jifeng},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  year={2024},
  publisher={IEEE}
}
```
