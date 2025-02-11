# Chest-X-Ray-Tags-Classification
This is the implementation of the visual model mentioned in our paper 'Automated Radiology Report Generation using Conditioned Transformers'.

Paper link [here](https://doi.org/10.1016/j.imu.2021.100557).

Thesis link [here](https://drive.google.com/file/d/1_FJdRVs5Saoqep6Gz40d_0nLsLbAgMeI/view?usp=drive_link).


We fine-tune a pre-trained Chexnet model to classify multiple tags given chest X-ray images from the IU-X-Ray dataset.

![image](https://user-images.githubusercontent.com/6074821/113486630-29b9d200-94b4-11eb-8189-dfc91793b3f8.png)

## Installation & Usage
*The project was tested on a virtual environment of python 3.7, pip 23.2.1, and MacOS*
- pip install -r full_requirements.txt (or pip install -r requirements.txt if there are errors because of using a different operating system, as requirements.txt only contains the main dependencies and pip will fetch the compatible sub-dependencies, but it will be slower)
- python get_iu_xray.py (to download the dataset)
- python train.py

## Related Repositories
- CDGPT2 repository (main paper repo) [here](https://github.com/omar-mohamed/GPT2-Chest-X-Ray-Report-Generation).
- VSGRU repository [here](https://github.com/omar-mohamed/X-Ray-Report-Generation).

## Citation
To cite this paper, please use:

```
@article{ALFARGHALY2021100557,
title = {Automated radiology report generation using conditioned transformers},
journal = {Informatics in Medicine Unlocked},
volume = {24},
pages = {100557},
year = {2021},
issn = {2352-9148},
doi = {https://doi.org/10.1016/j.imu.2021.100557},
url = {https://www.sciencedirect.com/science/article/pii/S2352914821000472},
author = {Omar Alfarghaly and Rana Khaled and Abeer Elkorany and Maha Helal and Aly Fahmy}
}
```

"# Finetuned-Chexnet" 
