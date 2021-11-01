# Istanbul University-Cerrahpasa dataset (IST-C) 
# High Resolution Computed Tomography Scans 

![Image of IST-C](https://github.com/verimsu/IST-C-dataset/blob/main/IST-C.png)

The dataset is collected at Istanbul University-Cerrahpasa, Cerrahpasa Faculty of Medicine
We have collected a new open-source dataset called IST-C, retrospectively from patients admitted to the Radiology department of Cerrahpasa Faculty of Medicine 
from March 2020 to August 2020. 

Download the dataset from [[Google Drive](https://drive.google.com/drive/folders/1VqP49qNvapCNTfjaff3eAQ23YtIDcKVN?usp=sharing)]

The collected dataset consists of 336 chest CT scans from COVID-19 infected patients, along with 245 scans showing normal lung parenchyma and 131 scans from Non-COVID-19 pneumonia, tumors and emphysema patients. 

The collected CT scans in DICOM format consists of 16-bit gray scale images of size 512x512. Each scan is accompanied with a set of personal attributes, such as patient ID, 
age, gender, location, date, etc. The average age of the patients is 52 +/- 17 years, in which 405 of the patients are male and 274 patients are female. 

The annotation of this dataset is at CT scan level: the CT of a patient as a whole is labelled as COVID-19, ''Normal'', or ''Other'' by expert radiologists at 
Istanbul University-Cerrahpaşa, Cerrahpaşa Faculty of Medicine. 



**License and Citation**

The use of this software is RESTRICTED to non-commercial research and educational purposes.

```
@article{ahmed2021covid,

  title={COVID-19 Detection in Computed Tomography Images with 2D and 3D Approaches},
  
  author={Ahmed, Sara Atito Ali and Yavuz, Mehmet Can and Sen, Mehmet Umut and Gulsen, Fatih and Tutar, Onur and Korkmazer, Bora and Samanci, Cesur and Sirolu, Sabri and Hamid, Rauf and Eryurekli, Ali Ergun and others},
  
  journal={arXiv preprint arXiv:2105.08506},
  
  year={2021}
  
}
```
