# Leukemia-Detection

CLASSIFICATION MODELS FOR THE DIAGNOSIS OF ACUTE LYMPHOBLASTIC LEUKEMIA

Leukemia is a type ofcancer that manifests itself with the proliferation of blood cells, especially white blood cells. This hematological disease is usually diagnosed using manual methods such as complete blood count, bone marrow aspiration, or microscopic examination of the blood sample. Manual methods of leukemia diagnosis are low-cost; however, they are less reliable, time-consuming, and labor-intensive methods. Abnormal white blood cells spread very quickly and also target other organs in the body. Therefore, early diagnosis of leukemia is critical. In addition, manual diagnosis methods results may differ according to the current psychological and physiological state of the medical personnel. Although the transition from manual methods to computer-aided diagnosis systems will increase the cost, it is of great importance in terms of providing doctors and laboratory technicians with a second opinion for definitive diagnosis.

This study developed hybrid classification models that aim to achieve high performance by using ***Transfer Learning*** and ***Ensemble Learning*** algorithms on microscopic blood images in the ***ALL-IDB dataset***, which is widely used in the literature for the diagnosis of Acute Lymphoblastic Leukemia (ALL).

Furthermore, the original images for this disease classification, it is also used in different preprocessing techniques, which are frequently used in the literature and have proven to give satisfactory outcomes by increasing the overall performance of the system. Finally, after applying all the methods mentioned above, ***100% accuracy*** on the ALL-IDB1 dataset was achieved.

***For more detailed information you can check out the presentation or the thesis paper.***

***Dataset:***

[https://scotti.di.unimi.it/all/](https://scotti.di.unimi.it/all/)

### How to run & test the project

1. Download the ALL-IDB1 dataset. By filling out the aplication located in the following link [https://scotti.di.unimi.it/all/#download](https://scotti.di.unimi.it/all/#download) you will gain acces to the dataset prepared by  Università degli Studi di Milano.
2. Modify the paths of the dataset in the given code to match your datasets path.
3. In this project Python 3.9.16 is used. Make sure that the packages are compatible with your Python version.
4. Run the OpenCV_Data_Augmentation.ipynb file to augment your data.
5. Run the tranfer-learning.ipynb file to generate models in any desired pre-trained image classification networks.
6. Pick minimum 2 of the generated models assign them in to ensemble-learning.ipynb file to create the ensemble learning model.
