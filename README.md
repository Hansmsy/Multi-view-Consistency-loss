# Multi-view-Consistency-loss
This is the official implementation of Multi-view Consistency loss (MCL).

## Main Results
**CASIA-B**
| Models | Methods | `Rank@1.NM` | `Rank@1.BG` | `Rank@1.CL` | Download checkpoint |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Gaitset |  Triplet loss | 95.8 | 90.0 | 75.4 | - |
| GaitBase |  Triplet loss | 97.6 | 94.0 | 77.4 | - |
| GaitBase | MCL | 98.2 | 94.0 | 77.6 | [model](https://huggingface.co/Hansmsy/Multi-view-Consistency-loss/resolve/main/CASIA-B/Baseline/GaitBase_DA/checkpoints/GaitBase_DA-60000.pt) |

**GREW**
| Models | Methods | `Rank@1` | `Rank@5` | `Rank@10` | Download checkpoint |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Gaitset |  Triplet loss | 46.3 | 63.6 | 70.3 | - |
| GaitBase |  Triplet loss | 60.1 | - | - | - |
| GaitBase | MCL | 61.2 | 75.9 | 81.1 | [model](https://huggingface.co/Hansmsy/Multi-view-Consistency-loss/resolve/main/GREW/Baseline/GaitBase_DA/checkpoints/GaitBase_DA-180000.pt) |

**Gait3D**
| Models | Methods | `Rank@1` | `Rank@5` | `mAP` | Download checkpoint |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Gaitset |  Triplet loss | 36.7 | 58.3 | 30.0 | - |
| GaitBase |  Triplet loss | 64.6 | - | - | - |
| GaitBase | MCL | 66.6 | 80.2 | 55.7 | [model](https://huggingface.co/Hansmsy/Multi-view-Consistency-loss/resolve/main/Gait-3D/Baseline/GaitBase_DA/checkpoints/GaitBase_DA-60000.pt) |
|  DeepGaitV2-P3D |  Triplet loss | 74.4 | - | - | - |
|  DeepGaitV2-P3D |  Interval Sampling | 75.5 | - | - | [model](https://huggingface.co/Hansmsy/Multi-view-Consistency-loss/resolve/main/Gait-3D/DeepGaitV2/DeepGaitV2/checkpoints/DeepGaitV2-60000.pt) |
