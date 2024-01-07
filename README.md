# Cancer_Detection
STEPS:

Detect the stage of the cancer by examining the size of the tumour
4 stages:
Mammography 


Ways:
Mammography: VinDr Mammo dataset.



Division of the project:
Mammograph: why done first?
A mammogram is a low-dose x-ray picture of the breast. Mammograms are the best primary screening tool to find breast cancer. They can find breast lumps early before lumps are big enough to feel or cause symptoms. Early detection of breast cancer can lead to early treatment options and better chances of survival.
LINKS:


https://www.hindawi.com/journals/jnm/2022/2641239/


CNN:
https://towardsdatascience.com/building-a-convolutional-neural-network-cnn-in-keras-329fbbadc5f5

LINK TO DATASET: MAMMOGRAPH DATA…
https://www.kaggle.com/datasets/awsaf49/cbis-ddsm-breast-cancer-image-dataset
:: the dataset is not processed, need to do image processing.

Breast Cancer Detection in Mammography Images: A CNN-Based Approach with Feature Selection
Kaggle competition to detect breast cancer: 
RSNA Screening Mammography Breast Cancer Detection | Kaggle


Dataset access:
https://www.cancerimagingarchive.net/collection/cbis-ddsm/
Code examples:
https://www.kaggle.com/code/markclyne95/cbis-ddsm-breast-cancer-image-dataset-training

CODE:
 https://colab.research.google.com/drive/10cBT64rnzfNlvVubQnW39Nk79WkrOGYj?usp=sharing

SOME INFORMATION ABOUT THE DATA:
1. DIVIDED INTO TWO - CALC_CASE AND MASS_CASE where one is regarding calcification while the other is about accumulation of cells.
Calc_case:
Calcifications: Calcifications are tiny deposits of calcium in the breast tissue. They appear as small white spots on a mammogram. While calcifications can be benign, certain patterns or types of calcifications may raise concerns and require further evaluation to determine if they are indicative of breast cancer.

Characteristics: The "calc_case" category in a breast cancer imaging dataset would likely include cases where the primary finding or abnormality is related to calcifications. This could involve providing information about the type, distribution, and other characteristics of the calcifications.

Mass_case:
Masses: Masses refer to abnormal growths or lumps in the breast tissue. They may appear as dense, rounded shapes on a mammogram. Masses can be benign or malignant, and distinguishing between the two is crucial for proper diagnosis and treatment planning.

Characteristics: The "mass_case" category in a breast cancer imaging dataset is likely to include cases where the primary finding is a mass. Information associated with "mass_case" would typically include details about the size, shape, margins, and other features of the identified masses.

ROI - region of interest
ROI stands for "Region of Interest," and ROI images refer to specific portions or regions within a larger image that are of particular interest for analysis or examination. In the context of medical imaging, including mammograms or other types of scans, ROI images are often cropped or selected areas that contain important information for diagnosis, research, or other purposes.


Mass Margins
Spiculated - Spiculated masses are characterized by lines of varying length and thickness radiating from the margins of the mass. Unless it is the site of a previous biopsy, a spiculated margin is very suspicious for malignancy.
Circumscribed - Well-defined margins with abrupt interface between mass and surrounding tissue.
Ill-defined - An ill-defined margin is a nonspecific finding that can be observed in both benign and malignant nodules. 
Obscured -  An obscured margin is one that is hidden by superimposed or adjacent fibro glandular tissue.


Breast Cancer Mass Types
Malignant - Malignant tumors have cells that grow uncontrollably and spread locally and/or to distant sites. Malignant tumors are cancerous (ie, they invade other sites). They spread to distant sites via the bloodstream or the lymphatic system. This spread is called metastasis.
Benign - A benign tumor is an abnormal but noncancerous collection of cells also called a benign neoplasm. Benign tumors can form anywhere on or in your body, but many don't need treatment. 
Benign without Callback - The term benign without callback is used to identify benign cases in which no additional films or biopsy was done to make the benign finding. 


The term "breast cancer mass subtlety" likely refers to the difficulty in detecting or characterizing a breast cancer mass on imaging studies due to subtle or inconspicuous features. In breast imaging, subtlety may refer to findings that are not easily distinguishable or may not exhibit classic characteristics of malignancy.

Different types of Fibroglandular density (the breast density vs pathology graphs)





CODE TO BE FOLLOWED:
https://www.kaggle.com/code/ankuraxz/resnet50-mobile/notebook




References

https://my.clevelandclinic.org/health/articles/22874-fibroglandular-density

ERROR IN PATH LOCATION ENCOUNTERED:

