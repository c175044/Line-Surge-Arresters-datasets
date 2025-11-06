# LSA Point Cloud Dataset

## Project Introduction

This project releases an open-source dataset containing annotated LSA point cloud instances. Each point cloud file is in TXT format, suitable for tasks such as point cloud classification and segmentation. Both academic and industrial communities are welcome to use this dataset for related research. Now we have uploaded part of the data. The complete data will be uploaded by November 30, 2025. Please wait patiently.

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
1.234 2.345 3.456 1
2.111 3.222 4.333 2
...
```

## Category Description

| label | Category Name           |
|-------|------------------------|
| 1     | Pylon                  |
| 2     | Power line             |
| 3     | Insulato               |
| 4     | Line surge arrester    |



## Data Download

Due to GitHub's file size limitations, the complete dataset can be downloaded via the following link:

- [Google Drive:https://drive.google.com/file/d/1L3r1ZAub8Pc2aV-LL61mJJBHl4oKKUn5/view?usp=drive_link]
- [OneDrive:https://1drv.ms/u/c/ef389807d02ff661/EZ7GLTVLRcBBvdoraTA4eDYBiyF4QqKRxETTBB8sFnq3pA?e=Kh3afS]



## License

This project is licensed under the CC BY 4.0 license. See the LICENSE file for details. 
