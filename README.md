# BurnAId
Skin Burn Classification App that implements a MobileNet-V3 based CNN Model to classify burns as 1st, 2nd and 3rd degree. <br>
Image Dataset derived from Kaggle https://www.kaggle.com/datasets/faresabbasai2022/skin-burn-dataset <br>
The model was trained on PyTorch environment with 1200 images, split in train, valid and test sets in the ratio 70/15/15. The CNN model acheived an accuracy of 89%. <br><br>
The model was then exported using TorchScript and integrated into an Android application developed in a Flutter framework using Dart language.<br>
The app has Google Maps redirection for nearest burn treatment centers, dial Emergency Hotline in case of a 3rd degree burn, along with first-aid advice.



