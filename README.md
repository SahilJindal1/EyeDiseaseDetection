# EyeDiseaseDetection

Data:
https://drive.google.com/drive/folders/1l0fKooIGeH2EHqJB0ldJ9QAwZPcw_Nuc?usp=sharing

Contrastive Learning:
https://lilianweng.github.io/lil-log/2021/05/31/contrastive-representation-learning.html#contrastive-training-objectives

Base Paper: https://sci-hub.hkvisa.net/10.1109/ICINPRO43533.2018.9096838

Kaggle Dataset: https://www.kaggle.com/andrewmvd/retinal-disease-classification

Drive Link of everything: https://drive.google.com/drive/folders/1JqHqWI_7QTBA6-uOTD4KM4YBn53qf6w4?usp=sharing


Flow:
1) Project/ImageResizer.ipynb: Resizes fundus images in Project/OriginalDataset from original size to 500x300 and stores in Project/Resized folder
2) FundusReadIntoArray.ipynb: Reads resized images from Project/Resized into numpyarray and stores respective numpy array at Project/Preprocessed into as TrainData.npy and TrainLabels.npy
3) NewModel.ipynb: Reads numpy arrays from step2 and classifies them using CNN model arch
