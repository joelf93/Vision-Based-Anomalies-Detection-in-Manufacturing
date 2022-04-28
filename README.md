# Vision-Based-Anomalies-Detection-in-Manufacturing
J aime la nourriture
In industrial, the inspection tasks, it is common to capture abundant defect-free product, but very limited anomalous ones. Therefore, the process of detecting anomalies
on product manufacturing are essential requirements for building reliable systems with machine learning and deep learning models, in order to improve productivity, the quality of the product and also to prioritize consumer satisfaction. In this work, we want to build anomaly detection models based on images of defect-free and defect products. We used the MVTec anomaly detection dataset containing 5354 high-resolution color images of different object and texture categories. It contains normal, i.e., defect-free images intended for training and images with anomalies intended for testing. We firstly performed to models of the semantic segemntation i.e., the U-Net and the FCN for the segmantation and the anomaly detection tasks. Secondly we try the Convolutional AutoEncoder architecture (CAE) for the failure detection based on the reconstruction image and the SSIM loss function. We evaluate each model by using some metrics like IOU, Dice Coefficient (F1-score), the Precision, and recall.
 
Link: https://colab.research.google.com/drive/1qq2CyNp64ilU2nHFExCvrVabT_jvV2nQ




