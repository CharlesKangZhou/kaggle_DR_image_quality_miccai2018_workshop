# Code
To be released

# paper
Fundus Image Quality-Guided Diabetic Retinopathy Grading
https://link.springer.com/chapter/10.1007/978-3-030-00949-6_29

# Kaggle DR dataset
EyePACS: Diabetic retinopathy detection. https://www.kaggle.com/c/diabetic-retinopathy-detection/data


# Kaggle DR Image Quality Dataset
**The funds image quality label is provided by iMed.**(homepage: http://imed.nimte.ac.cn/;http://imed.nimte.ac.cn/aboutus.html)

## Four instances of poor quality images in Kaggle DR dataset
![fig1](images/fig1.png)
The quality of these images are too poor to identify the lesion.

## Unbalanced ratio
In our Kaggle DR image quality dataset, the number of good and poor quality images are shown as follows. The ratio is extremely unbalanced.
![table1](images/table1.png)

## Quality Label
The csv files are in *quality_csv_label*

  _quality_label_train.csv_
  
  _quality_label_validate.csv_
  
  _quality_label_test.csv_

  **0 denotes poor quality**
  
  **1 denotes good quality**


# Citation
If you find this useful, please cite our work as follows:

@incollection{zhou2018fundus,
  title={Fundus Image Quality-Guided Diabetic Retinopathy Grading},
  author={Zhou, Kang and Gu, Zaiwang and Li, Annan and Cheng, Jun and Gao, Shenghua and Liu, Jiang},
  booktitle={Computational Pathology and Ophthalmic Medical Image Analysis},
  pages={245--252},
  year={2018},
  publisher={Springer}
}
