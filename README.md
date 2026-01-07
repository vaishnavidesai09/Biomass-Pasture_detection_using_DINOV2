
# Pasture Detection using DINOv2



## Overview

This project leverages **DINOv2**, a self-supervised vision transformer model, to detect and analyze pasture regions from aerial or satellite imagery. By extracting meaningful visual features, this system can help in agricultural monitoring, land use analysis, and sustainable pasture management.

---

## Features

* Detects pasture areas from high-resolution images.
* Uses **self-supervised feature extraction** via DINOv2 for accurate segmentation.
* Generates clear visualizations to distinguish pasture regions from other land types.
* Can be adapted for other vegetation or land cover detection tasks.
* Supports batch processing for large datasets.

---

## Dataset

* Input images can be high-resolution satellite or drone-captured images of pasture regions.
* Images should be stored in a structured directory, e.g.,

```
data/
 ├── train/
 │    ├── img1.jpg
 │    ├── img2.jpg
 └── test/
      ├── img1.jpg
      
```

* Optional: Metadata (NDVI, season, region) can be included for enhanced analysis.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/vaishnavidesai09/pasture-detection-dinov2.git
cd pasture-detection-dinov2
```

**Dependencies include:**

* `torch`
* `torchvision`
* `dinov2`
* `numpy`
* `matplotlib`
* `PIL`
* `opencv-python`



---

## Model

* Uses **DINOv2 Vision Transformer** for self-supervised feature extraction.
* Works without labeled datasets, making it ideal for new or unlabeled imagery.
* Extracted features are clustered or thresholded to identify pasture regions.

---



## References

* [DINOv2 Official Paper](https://arxiv.org/abs/2304.07193)
* [DINOv2 GitHub Repository](https://github.com/facebookresearch/dinov2)

---


