# BROOK Dataset
BROOK Dataset, a multi-modal and facial video dataset for data-driven Human-Vehicle Interaction.

## Dataset Overview

### Dataset Structure
The current version of BROOK dataset has a total of 11 dimensional data, includng facial videos and many multi-modal/driving status data of 34 drivers.

![avatar](/img/Structure.png)

### Dataset Size
|Facial Video|Heart Rates|Skin Conductance|Eye Tracking|Driving Status|
|-           |-          |-               |-           |-             |
|273GB       |13.1MB     |48.3MB          |27.2GB      |60.9MB        |

### Unique Features of BROOK
- **Automated Mode**
  We collect data from both manual driving mode and automated mode.
- **Region-based Customization**
  We customize our scenarios and scenes based on the common patterns of roads in China,
- **Eye-Tracking Statistics**
  We collect Eye-Tracking statistics (fixations and pupil-size variation) via a Tobii Eye-Tracking device.


## Example Studies based on BROOK
- **Demystifying interactions between driving behaviors and styles through self-clustering algorithms**
  ```
  @inproceedings{HCI21/DBSCAN,
        title={{Demystifying interactions between driving behaviors and styles through self-clustering algorithms}},
        author={Zhang, Yu and Jin, Wangkai and Xiong, Zeyu and Li, Zhihao and Liu, Yuyang and Peng, Xiangjun},
        booktitle={HCI in Mobility, Transport, and Automotive Systems: Third International Conference, MobiTAS 2021, Held as Part of the 23rd HCI International Conference, HCII 2021, Virtual Event, July 24--29, 2021, Proceedings},
        pages={335--350},
        year={2021},
        organization={Springer}
    }
  ```
- **Characterizing and Optimizing Differentially-Private Techniques for High-Utility, Privacy-Preserving Internet-of-Vehicles**
  ```
  @inproceedings{hci23/DP-IoV,
        author    = {Yicun Duan and
                    Junyu Liu and
                    Xiaoxing Ming and
                    Wangkai Jin and 
                    Zilin Song and 
                    Xiangjun Peng},
        title     = {{Characterizing and Optimizing Differentially-Private Techniques for High-Utility, Privacy-Preserving Internet-of-Vehicles}},
        booktitle = {{International Conference on Human-Computer Interaction}},
        year      = {2023}
    }

  @article{arxiv22/DP-Characterize,
        author    = {Yicun Duan and
                    Junyu Liu and
                    Wangkai Jin and
                    Xiangjun Peng},
        title     = {{Characterizing Differentially-Private Techniques in the Era of Internet-of-Vehicles}},
        howpublished = {{Technical Report-Feb-03 at User-Centric Computing Group, University of Nottingham Ningbo China}},
        year      = {2022}
    }

  @article{arxiv22/DP-HUT,
        author    = {Junyu Liu and
                    Wangkai Jin and
                    Zhenyong He and
                    Xiaoxing Ming and
                    Yicun Duan and
                    Zeyu Xiong and
                    Xiangjun Peng},
        title     = {{HUT: Enabling High-UTility, Batched Queries under Differential Privacy Protection for Internet-of-Vehicles}},
        howpublished = {{Technical Report-Feb-02 at User-Centric Computing Group, University of Nottingham Ningbo China}},
        year      = {2022}
    }
  ```
- **Face2Statistics: User-Friendly, Low-Cost and Effective Alternative to In-Vehicle Sensors/Monitors for Drivers**
  ```
  @inproceedings{HCI22/Face2Statistics,
        title={Face2Statistics: user-friendly, low-cost and effective alternative to in-vehicle sensors/monitors for drivers},
        author={Xiong, Zeyu and Wang, Jiahao and Jin, Wangkai and Liu, Junyu and Duan, Yicun and Song, Zilin and Peng, Xiangjun},
        booktitle={HCI in Mobility, Transport, and Automotive Systems: 4th International Conference, MobiTAS 2022, Held as Part of the 24th HCI International Conference, HCII 2022, Virtual Event, June 26--July 1, 2022, Proceedings},
        pages={289--308},
        year={2022},
        organization={Springer}
    }
  ```

## Access to BROOK Dataset
Please send email to ```ljunyu381@gmail.com```

## Citation for BROOK Dataset
```
@inproceedings{hci23/brook,
    author    = {Junyu Liu and 
                Yicun Duan and 
                Zhuoran Bi and 
                Xiaoxing Ming and 
                Wangkai Jin and 
                Zilin Song and 
                Xiangjun Peng},
    title     = {{BROOK Dataset: A Playground for Exploiting Data-Driven Techniques in Human-Vehicle Interactive Designs}},
    booktitle = {{International Conference on Human-Computer Interaction}},
    year      = {2023}
}

@article{BROOK,
    author    = {Xiangjun Peng and
                    Zhentao Huang and
                    Xu Sun},
    title     = {{Building BROOK: A Multi-modal and Facial Video Database for Human-Vehicle Interaction Research}},
    booktitle = {{the 1st Workshop of Speculative Designs for Emergent Personal Data Trails: Signs, Signals and Signifiers, co-located with  the 2020 {CHI} Conference on Human Factors in Computing Systems, ({CHI}), Honolulu, HI, USA, April 25-30, 2020}},
    pages     = {1--9},
    publisher = {{arXiv}},
    year      = {2020},
    url       = {https://arxiv.org/abs/2005.08637},
    eprint    = {2005.08637}
}
```