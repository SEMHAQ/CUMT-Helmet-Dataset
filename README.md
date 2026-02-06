# CUMT-Helmet-Dataset
en-version:

This dataset focuses on safety helmet images in complex scenarios.
The dataset includes coal mine environments; as the image targets are relatively uniform, to expand the dataset, images from other safety helmet datasets underwent complex scenario processing. Simultaneously, images were re-annotated with new categories.
The dataset comprises two categories: helmet (wearing a safety helmet) and no-helmet (not wearing a safety helmet).

As this dataset is compiled from multiple sources, label contamination exists. This project addresses classification issues and converts the dataset to YOLO format.
Processing logic is as follows:
‘Safety helmet’ & “Hat” -- ‘1’
“Person” & ‘No safety helmet’ -- ‘0’
All other cases are ignored.

Please note this dataset originates from https://github.com/CUMT-AIPR-Lab/CUMT-AIPR-Lab. This project merely shares and makes minor enhancements; ensure appropriate usage.

cn-version:

本数据集面对的是复杂场景的安全帽图片，
数据集中包含有煤矿场景，因图片目标较为单一，为扩充数据集，对其他安全帽数据集的图片进行了复杂场景的处理，同时重新使用新的类标注图片。
数据集包括两个类：helmet、no-helmet。

由于该数据集是拼接而成，标签杂乱，本项目并对分类进行了处理，并将数据集转化成YOLO格式。
处理逻辑如下：
'helmet'&'hat' -- '1'
'people'&'no-helmet' --'0'
对于其他的皆忽略处理。

请注意，该数据集来源https://github.com/CUMT-AIPR-Lab/CUMT-AIPR-Lab。本项目仅分享并进行少量改进，请确保合理用途。



