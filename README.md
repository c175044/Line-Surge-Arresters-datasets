# LSA Point Cloud Dataset

## Project Introduction

This project releases an open-source dataset containing 896 annotated LSA point cloud instances. Each point cloud file is in txt format, suitable for tasks such as point cloud classification and segmentation. Both academic and industrial communities are welcome to use this dataset for related research. The data will be uploaded by November 30, 2025. Please wait patiently.

## Dataset Structure

```
dataset-lsa/
├── data/
│   ├── 0001.txt
│   ├── 0002.txt
│   └── ...
├── README.md
└──LICENSE
```

- `data/`: Stores all point cloud txt files.
- `README.md`: Project documentation.
- `LICENSE`: Open source license.

## Data Format Description

Each point cloud file is in `.txt` format, with each line representing a point and containing four columns:

| Column | Meaning | Description |
|--------|---------|-------------|
| 1      | x       | x coordinate (float) |
| 2      | y       | y coordinate (float) |
| 3      | z       | z coordinate (float) |
| 4      | label   | Category (integer/string, see table below) |

**Example:**
```
1.234 2.345 3.456 0
2.111 3.222 4.333 1
...
```

## Category Description

| label | Category Name           |
|-------|------------------------|
| 1     | Pylon                  |
| 2     | Power line             |
| 3     | Line surge arrester    |
| 4     | Insulator              |


> Please fill in the actual category names according to your dataset.

## Data Download

Due to GitHub's file size limitations, the complete dataset can be downloaded via the following link:

- [Baidu Netdisk/Google Drive/Aliyun Drive, etc.] (Please fill in the download link here)

This repository only provides a subset of sample data.

## Citation

If you use this dataset in your research, please cite:

```
@misc{lsa_pointcloud_dataset,
  title={LSA Point Cloud Dataset},
  author={Your Name},
  year={2024},
  howpublished={\url{https://github.com/yourname/dataset-lsa}}
}
```

## License

This project is licensed under the CC BY 4.0 license. See the LICENSE file for details. 
