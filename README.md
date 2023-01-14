# DICOM-Using-Python

If you are a **Biomedical Engineer**, an **IT Specialist in the healthcare field**, or a **Healthcare Data Scientist/Analyst**, you’ve probably used or at least heard about DICOM because it’s everywhere related to medical imaging systems. DICOM is a set of standards that are created to allow communication across multiple modalities between multiple manufacturers so that all medical machines, that are DICOM-compliant of course, can speak the same language when sending information across a network. All you need is one piece of software, a DICOM reader, to read many medical DICOM images from many different modalities.

For more information about **DICOM**, refer to this **[post](https://medium.com/@omar.ok1998/what-is-dicom-a28c5fe24c9d)**.

There are a lot of DICOM samples on the internet. And you can use your own DICOM files. I chose a [dataset](https://www.kaggle.com/datasets/dmisky/dlwptvolumetricdicomlung) of 99 slices of chest-CT scans for one patient. You can find it on Kaggle. I saved the dataset on my [Drive](https://drive.google.com/drive/folders/1dbJpXVUBn0mSUxgJIqKZj4d_0thSeTW3?usp=sharing) so I can easily have access through GoogleColab.

## Dealing with DICOM Using ImageIO Python Package: [[TDS]](https://towardsdatascience.com/dealing-with-dicom-using-imageio-python-package-117f1212ab82)  [[Code]](https://github.com/OmarAlkousa/DICOM-Using-Python/blob/main/Dealing_with_DICOM_using_%20ImageIO/Dealing_with_DICOM_using_%20ImageIO.ipynb)
Using the **ImageIO** Python package to **read DICOM files**, **extract metadata** and attributes, and plot image slices using **interactive** slider widgets using **Ipywidgets**. While doing so, we have to understand some important DICOM attributes such as **Pixel Spacing**, **Shape**, **Slice Thickness**, and **Aspect Ratio**.



<p align="center">
  <img src="https://github.com/OmarAlkousa/DICOM-Using-Python/blob/main/Dealing_with_DICOM_using_%20ImageIO/Demo/Axial_Coronal_Sagittal_CT_DEMO.gif", width="600">
</p>

## Introducing PyDicom, its Classes, Methods, and Attributes: [[TDS]](https://medium.com/towards-data-science/introducing-pydicom-its-classes-methods-and-attributes-518c1d71162) [[Code]](https://github.com/OmarAlkousa/DICOM-Using-Python/blob/main/DICOM_Using_PyDicom/Introducing_PyDicom%2C_its_Classes%2C_Methods%2C_and_Attributes.ipynb)
If you are a Pythonista and you're working with Medical Data, especially DICOM data, you've probably heard of the great python package PyDicom. You'll learn the basics of this package. We'll discuss PyDicom classes (DataSet, DataElement, Sequence) and some useful methods and attributes that you can apply to PyDicom classes.

<p align="center">
  <img src="https://github.com/OmarAlkousa/DICOM-Using-Python/blob/main/DICOM_Using_PyDicom/Reading_DICOM_File_Using_dcm_read.png", width="600">
</p>

## From DICOM to CSV File: [[Code]](https://github.com/OmarAlkousa/DICOM-Using-Python/blob/8d945b91ac2facee0f28940665dd547d7c62a07a/From_DICOM_to_CSV_File/From_DICOM_Header_to_CSV%20File.ipynb)
DICOM files consider data beyond pixel data and store it as a DICOM header. Such data are the Patient's age and weight, Modality, Image Dimension, and so on. In this post, we will use the PyDicom package to build a Python function that can extract specific metadata to use in further data analysis work.

<p align="center">
  <img src="https://github.com/OmarAlkousa/DICOM-Using-Python/blob/8d945b91ac2facee0f28940665dd547d7c62a07a/From_DICOM_to_CSV_File/DICOM%20TO%20CSV.png", width="600">
</p>

**SUBSCRIBE  on [MEDIUM](https://medium.com/@omar.ok1998/subscribe)**.

Keep in touch: [LinkedIn](https://www.linkedin.com/in/omar-alkousa).

