
# Utilizing Blind freehand ultrasound sweeps to determine fetal viability

This repository contains the codes (in PyTorch) for the framework introduced in the following paper:

This repository is largely based on the works cited below:
[[Paper]](https://www.sciencedirect.com/science/article/pii/S136184152100044X) [[Project Page]](https://pakheiyeung.github.io/PlaneInVol_wp/)


```
@article{yeung2021learning,
	title = {Learning to map 2D ultrasound images into 3D space with minimal human annotation},
	author = {Yeung, Pak-Hei and Aliasi, Moska and Papageorghiou, Aris T and Haak, Monique and Xie, Weidi and Namburete, Ana IL},
	journal = {Medical Image Analysis},
	volume = {70},
	pages = {101998},
	year = {2021},
	publisher = {Elsevier}
}
```
## Contents
1. [Dependencies](#dependencies)
2. [Train](#train)
3. [Inference on Video Data](#inference-on-video-data)


## Dependencies
- Python (3.6), other versions should also work
- PyTorch (1.6), other versions should also work 
- scipy
- cv2
- skimage
- [imgaug](https://imgaug.readthedocs.io/en/latest/)

## Train
1. Modify the `train_github.py` for importing your dataset according to the instructions in the file.
2. Use the following command to train:
	```
	python train_github.py
	```
## Inference on Video Data
### Post (predict after the whole video is acquired)
1. Modify the `inference_github.py` according to the instructions in the file.
2. Use the following command to train:
	```
	python inference_github.py
	```
### Real-time 
To do, but it would be an easy modification based on the `inference_github.py`.
