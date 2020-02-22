# Image Captioning in Human-like Manner

## Requirements
1. Python 3.6 (tensorflow pls)
2. Microsoft Visual C++ Build Tools. [Get them here](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools&rel=16). (Download will start automatically).

    Download and let it run. Select Visual C++ Build tools (the first option) and let it download and install (total size is ~4.6GB, so kick back and relax...)

## Setup
1. Please download, unzip, and place the images in: coco/images/
2. Please download and place the annotations in: coco/annotations/
3. `python -m venv venv`
4. `.\venv\Scripts\activate`
5. `pip install -r requirements.txt`
6. `jupyter lab`
7. Experiment and attempt to load all images and captions with the `pycocotools` API library. Use `pycocoDemo` notebook for reference.