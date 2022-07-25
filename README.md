# Homework-3D-object-detection-MMdetection3D:

# Introduction 
Name : Rohan Deshmukh  || (015214329)
Course : CMPE249-IA  || (San Jose State University)

### Part 1 - setup :

Link for reference - https://mmdetection3d.readthedocs.io/en/latest/getting_started.html

### Part 1 - Screenshots of execution -

<img width="1440" alt="Screen Shot 2022-07-24 at 6 25 20 PM" src="https://user-images.githubusercontent.com/78194318/180706493-eea30733-8716-4e96-bbf5-c4655911cc1a.png">
<img width="1440" alt="Screen Shot 2022-07-24 at 6 25 36 PM" src="https://user-images.githubusercontent.com/78194318/180706512-e12c6fc0-be5b-4e5d-be21-565d487e9a6a.png">
<img width="1440" alt="Screen Shot 2022-07-24 at 6 25 46 PM" src="https://user-images.githubusercontent.com/78194318/180706528-98e4d2e3-e284-448b-94cb-3db5b319e658.png">

### Part 2 - MMdetection3D github setup 

GitHub Link - git clone https://github.com/open-mmlab/mmdetection3d.git

Install Cuda, tensorflow, all other prerequisite from the mentioned documentation.

### Part 3 - Epoch execution 

<img width="1440" alt="Screen Shot 2022-07-24 at 7 13 58 PM" src="https://user-images.githubusercontent.com/78194318/180707103-a5947f40-fb35-4a8f-a80f-a818d000df3b.png">
<img width="1440" alt="Screen Shot 2022-07-24 at 7 25 47 PM" src="https://user-images.githubusercontent.com/78194318/180707108-c12a840d-750f-4bf6-b0e3-7ead2a9ec442.png">
<img width="1440" alt="Screen Shot 2022-07-24 at 7 48 18 PM" src="https://user-images.githubusercontent.com/78194318/180707112-9d131178-5104-4742-93aa-64f85c673ab6.png">
<img width="1440" alt="Screen Shot 2022-07-24 at 7 55 27 PM" src="https://user-images.githubusercontent.com/78194318/180707114-6a23e46f-13eb-4156-9553-9858cd9d9115.png">

### Part 4 - Evaluation Metrics 

###### Introduction
Calculate overlap between two set of bboxes.
If is_aligned is False, then calculate the ious between each bbox of bboxes1 and bboxes2, otherwise the ious between each aligned pair of bboxes1 and bboxes2.

###### Command 
bash tools/dist_test.sh configs/pointpillars/hv_pointpillars_secfpn_6x8_160e_kitti-3d-3class.py work_dirs/hv_pointpillars_secfpn_6x8_160e_kitti-3d-3class/latest.pth 1 --eval bbox

<img width="1440" alt="Screen Shot 2022-07-24 at 8 26 44 PM" src="https://user-images.githubusercontent.com/78194318/180707825-3c4eb973-8da5-4e2b-841b-87172bc533c7.png">
<img width="1440" alt="Screen Shot 2022-07-24 at 8 26 47 PM" src="https://user-images.githubusercontent.com/78194318/180707836-6009ec04-7024-4c5e-88a2-b170f34cc6bf.png">
<img width="1440" alt="Screen Shot 2022-07-24 at 8 26 49 PM" src="https://user-images.githubusercontent.com/78194318/180707843-d1af0ae4-5048-40d6-b76b-8ae06a4cc8d4.png">
<img width="1440" alt="Screen Shot 2022-07-24 at 8 30 09 PM" src="https://user-images.githubusercontent.com/78194318/180707847-20337b74-20a5-48aa-b989-838d7e28f1a0.png">


### Part 5 - inference pipeline

<img width="1440" alt="Screen Shot 2022-07-24 at 9 39 34 PM" src="https://user-images.githubusercontent.com/78194318/180708081-58381d2d-70b1-4b58-9eb0-ae1be0a76634.png">
<img width="1440" alt="Screen Shot 2022-07-24 at 9 57 35 PM" src="https://user-images.githubusercontent.com/78194318/180708099-91d664a1-f8e6-4df1-9f1f-4125fd726439.png">
<img width="1440" alt="Screen Shot 2022-07-24 at 10 10 40 PM" src="https://user-images.githubusercontent.com/78194318/180708102-9c899a20-35e0-4809-87de-cf6be27ba24c.png">

