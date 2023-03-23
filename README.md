# Automatic High Resolution Wire Segmentation and Removal

Mang Tik Chiu<sup>1</sup>, Xuaner (Cecilia) Zhang<sup>2</sup>, Zijun Wei<sup>2</sup>, Yuqian Zhou<sup>2</sup>, Eli Shechtman<sup>2</sup>,
Connelly Barnes<sup>2</sup>, Zhe Lin<sup>2</sup>, Florian Kainz<sup>2</sup>, Sohrab Amirghodsi<sup>2</sup>, Humphrey Shi<sup>1,3</sup>

<sup>1</sup>UIUC, <sup>2</sup>Adobe, <sup>3</sup>University of Oregon

CVPR 2023
<a href="" target="_blank">Paper</a>

<img src="teaser.jpg" width="100%"/>

---

## WireSegHR Dataset

We release test images from our WireSegHR dataset. The images and annotations can be downloaded <a href="https://drive.google.com/drive/folders/1fgy3wn_yuHEeMNbfiHNVl1-jEdYOfu6p?usp=sharing" target="_blank">here</a>.

## Dataset folder structure

```
WireSegHR\
├── images\
│   ├── image_1.jpg\
│   ...
│   └── image_N.jpg\
│
└── gts\
    ├── image_1.png\
    ...
    └── image_N.png\
```

Annotations are paletted binary images with values 0 or 1.
