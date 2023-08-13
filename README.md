# S13 Assignment - Notebook

## S13.ipynb
The notebook clones yolov3.git repo using -

```
!git clone https://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@github.com/piygr/yolov3.git
```

The repo has a models folder which contains the [YoloV3Lightning.py](https://github.com/piygr/mainErav1/blob/main/models/custom_resnet_lightning_s10.py) file containing
**YOLOv3LightningModel** a LightningModule class.



If the repo is cloned, then move the yolov3 folder

```
%pwd
%cd yolov3
```
The notebook was built on Kaggle hence the dataset filepath is set accordingly.


We might have to install few packages for eg.
```
!pip install torch_lr_finder
!pip install grad-cam
!pip install pytorch-lightning
```

Once the packages are installed, we have to import functionalities from main.py & utils.py
can train & experiment with the model.
Sanity Checking: 0it [00:00, ?it/s]
Training: 0it [00:00, ?it/s]
Validation: 0it [00:00, ?it/s]
Epoch  0
Train -
Class accuracy is: 25.232008%
No obj accuracy is: 1.120628%
Obj accuracy is: 93.404297%
Total loss: 25.689705
Validation -
Class accuracy is: 35.807098%
No obj accuracy is: 7.207995%
Obj accuracy is: 67.440979%
Total loss: 20.051125
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  1
Train -
Class accuracy is: 33.195148%
No obj accuracy is: 60.821991%
Obj accuracy is: 29.544977%
Total loss: 14.212562
Validation -
Class accuracy is: 41.413261%
No obj accuracy is: 99.409050%
Obj accuracy is: 2.399970%
Total loss: 14.691023
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  2
Train -
Class accuracy is: 36.459782%
No obj accuracy is: 99.361130%
Obj accuracy is: 6.295816%
Total loss: 12.143026
Validation -
Class accuracy is: 42.099464%
No obj accuracy is: 99.705162%
Obj accuracy is: 5.581614%
Total loss: 13.952564
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  3
Train -
Class accuracy is: 39.861053%
No obj accuracy is: 97.736061%
Obj accuracy is: 26.232111%
Total loss: 11.083877
Validation -
Class accuracy is: 42.299511%
No obj accuracy is: 97.934685%
Obj accuracy is: 31.588655%
Total loss: 11.927257
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  4
Train -
Class accuracy is: 42.355675%
No obj accuracy is: 97.340378%
Obj accuracy is: 38.800068%
Total loss: 10.441254
Validation -
Class accuracy is: 38.022770%
No obj accuracy is: 98.061623%
Obj accuracy is: 27.454510%
Total loss: 13.814042
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  5
Train -
Class accuracy is: 45.546928%
No obj accuracy is: 97.241966%
Obj accuracy is: 44.253304%
Total loss: 9.779098
Validation -
Class accuracy is: 52.598667%
No obj accuracy is: 96.490440%
Obj accuracy is: 47.661011%
Total loss: 10.879908
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  6
Train -
Class accuracy is: 47.884693%
No obj accuracy is: 97.283264%
Obj accuracy is: 48.163826%
Total loss: 9.353159
Validation -
Class accuracy is: 46.616600%
No obj accuracy is: 97.089142%
Obj accuracy is: 46.860683%
Total loss: 11.597934
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  7
Train -
Class accuracy is: 49.925766%
No obj accuracy is: 97.307251%
Obj accuracy is: 51.911186%
Total loss: 8.956401
Validation -
Class accuracy is: 52.603287%
No obj accuracy is: 97.331474%
Obj accuracy is: 52.253109%
Total loss: 10.794819
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  8
Train -
Class accuracy is: 51.890884%
No obj accuracy is: 97.370743%
Obj accuracy is: 53.457481%
Total loss: 8.664756
Validation -
Class accuracy is: 51.493176%
No obj accuracy is: 97.139374%
Obj accuracy is: 50.187176%
Total loss: 10.448366
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  9
Train -
Class accuracy is: 53.788906%
No obj accuracy is: 97.419029%
Obj accuracy is: 55.303318%
Total loss: 8.381717
Validation -
Class accuracy is: 52.429825%
No obj accuracy is: 97.933167%
Obj accuracy is: 46.779312%
Total loss: 10.747021
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  10
Train -
Class accuracy is: 54.982384%
No obj accuracy is: 97.475227%
Obj accuracy is: 56.551003%
Total loss: 8.158789
Validation -
Class accuracy is: 55.940048%
No obj accuracy is: 95.638458%
Obj accuracy is: 65.424088%
Total loss: 10.625607
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  11
Train -
Class accuracy is: 56.145496%
No obj accuracy is: 97.501534%
Obj accuracy is: 57.869827%
Total loss: 7.944036
Validation -
Class accuracy is: 61.554646%
No obj accuracy is: 97.133179%
Obj accuracy is: 62.555416%
Total loss: 8.727653
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  12
Train -
Class accuracy is: 57.722557%
No obj accuracy is: 97.518250%
Obj accuracy is: 59.153400%
Total loss: 7.708074
Validation -
Class accuracy is: 62.757683%
No obj accuracy is: 97.045723%
Obj accuracy is: 63.676788%
Total loss: 8.197222
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  13
Train -
Class accuracy is: 58.984512%
No obj accuracy is: 97.478928%
Obj accuracy is: 61.043941%
Total loss: 7.495914
Validation -
Class accuracy is: 60.645943%
No obj accuracy is: 97.802299%
Obj accuracy is: 58.790951%
Total loss: 8.590283
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  14
Train -
Class accuracy is: 60.564156%
No obj accuracy is: 97.544441%
Obj accuracy is: 61.886723%
Total loss: 7.281298
Validation -
Class accuracy is: 65.732567%
No obj accuracy is: 96.980255%
Obj accuracy is: 67.176659%
Total loss: 8.033020
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  15
Train -
Class accuracy is: 62.253986%
No obj accuracy is: 97.539558%
Obj accuracy is: 63.508614%
Total loss: 7.034575
Validation -
Class accuracy is: 68.621193%
No obj accuracy is: 97.291740%
Obj accuracy is: 68.065056%
Total loss: 7.870706
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  16
Train -
Class accuracy is: 63.522255%
No obj accuracy is: 97.585312%
Obj accuracy is: 64.408325%
Total loss: 6.839924
Validation -
Class accuracy is: 69.154724%
No obj accuracy is: 96.975121%
Obj accuracy is: 69.191650%
Total loss: 7.981153
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  17
Train -
Class accuracy is: 64.894119%
No obj accuracy is: 97.604973%
Obj accuracy is: 65.875153%
Total loss: 6.631741
Validation -
Class accuracy is: 70.581749%
No obj accuracy is: 97.094933%
Obj accuracy is: 67.196175%
Total loss: 7.972373
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  18
Train -
Class accuracy is: 65.734673%
No obj accuracy is: 97.612404%
Obj accuracy is: 66.146927%
Total loss: 6.496179
Validation -
Class accuracy is: 70.185448%
No obj accuracy is: 97.528244%
Obj accuracy is: 68.013229%
Total loss: 7.528655
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  19
Train -
Class accuracy is: 67.433990%
No obj accuracy is: 97.644287%
Obj accuracy is: 67.498093%
Total loss: 6.290948
Validation -
Class accuracy is: 73.614563%
No obj accuracy is: 97.522064%
Obj accuracy is: 68.932465%
Total loss: 7.025859
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  20
Train -
Class accuracy is: 68.433121%
No obj accuracy is: 97.678635%
Obj accuracy is: 68.036598%
Total loss: 6.118616
Validation -
Class accuracy is: 73.071846%
No obj accuracy is: 97.434280%
Obj accuracy is: 70.346283%
Total loss: 7.827752
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  21
Train -
Class accuracy is: 69.808235%
No obj accuracy is: 97.696587%
Obj accuracy is: 69.038727%
Total loss: 5.951813
Validation -
Class accuracy is: 74.921852%
No obj accuracy is: 97.231659%
Obj accuracy is: 72.146217%
Total loss: 7.891651
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  22
Train -
Class accuracy is: 71.193565%
No obj accuracy is: 97.733856%
Obj accuracy is: 69.561218%
Total loss: 5.746172
Validation -
Class accuracy is: 73.792358%
No obj accuracy is: 97.469376%
Obj accuracy is: 73.478378%
Total loss: 6.359887
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  23
Train -
Class accuracy is: 72.032806%
No obj accuracy is: 97.759521%
Obj accuracy is: 70.275810%
Total loss: 5.630647
Validation -
Class accuracy is: 75.695854%
No obj accuracy is: 97.370003%
Obj accuracy is: 73.392952%
Total loss: 7.014555
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  24
Train -
Class accuracy is: 73.251411%
No obj accuracy is: 97.774803%
Obj accuracy is: 71.472160%
Total loss: 5.431481
Validation -
Class accuracy is: 77.794884%
No obj accuracy is: 97.876724%
Obj accuracy is: 72.454277%
Total loss: 6.472860
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  25
Train -
Class accuracy is: 74.416862%
No obj accuracy is: 97.814491%
Obj accuracy is: 71.792015%
Total loss: 5.263697
Validation -
Class accuracy is: 77.865685%
No obj accuracy is: 97.417793%
Obj accuracy is: 75.399330%
Total loss: 6.820900
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  26
Train -
Class accuracy is: 75.198624%
No obj accuracy is: 97.839645%
Obj accuracy is: 72.257881%
Total loss: 5.146402
Validation -
Class accuracy is: 78.675529%
No obj accuracy is: 97.771088%
Obj accuracy is: 73.627197%
Total loss: 6.898202
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  27
Train -
Class accuracy is: 76.144699%
No obj accuracy is: 97.852882%
Obj accuracy is: 73.079544%
Total loss: 4.998022
Validation -
Class accuracy is: 79.750641%
No obj accuracy is: 97.794662%
Obj accuracy is: 74.263039%
Total loss: 5.948236
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  28
Train -
Class accuracy is: 77.356430%
No obj accuracy is: 97.879044%
Obj accuracy is: 73.731964%
Total loss: 4.833117
Validation -
Class accuracy is: 79.157082%
No obj accuracy is: 97.410217%
Obj accuracy is: 76.789558%
Total loss: 6.004734
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  29
Train -
Class accuracy is: 78.452225%
No obj accuracy is: 97.924332%
Obj accuracy is: 74.268875%
Total loss: 4.701129
Validation -
Class accuracy is: 80.804131%
No obj accuracy is: 97.743294%
Obj accuracy is: 75.223114%
Total loss: 6.526340
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  30
Train -
Class accuracy is: 79.561058%
No obj accuracy is: 97.944115%
Obj accuracy is: 75.082680%
Total loss: 4.531520
Validation -
Class accuracy is: 81.060043%
No obj accuracy is: 97.748550%
Obj accuracy is: 76.468826%
Total loss: 5.420404
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  31
Train -
Class accuracy is: 80.253181%
No obj accuracy is: 97.957268%
Obj accuracy is: 75.236145%
Total loss: 4.419090
Validation -
Class accuracy is: 82.217178%
No obj accuracy is: 97.724030%
Obj accuracy is: 77.520721%
Total loss: 5.691806
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  32
Train -
Class accuracy is: 81.087143%
No obj accuracy is: 97.984810%
Obj accuracy is: 76.043114%
Total loss: 4.302423
Validation -
Class accuracy is: 82.440392%
No obj accuracy is: 97.903023%
Obj accuracy is: 76.796036%
Total loss: 5.737122
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  33
Train -
Class accuracy is: 82.000816%
No obj accuracy is: 97.975670%
Obj accuracy is: 76.496605%
Total loss: 4.196468
Validation -
Class accuracy is: 82.733803%
No obj accuracy is: 97.828262%
Obj accuracy is: 77.344170%
Total loss: 4.867690
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  34
Train -
Class accuracy is: 82.422005%
No obj accuracy is: 97.998421%
Obj accuracy is: 76.750145%
Total loss: 4.122161
Validation -
Class accuracy is: 82.726089%
No obj accuracy is: 97.905891%
Obj accuracy is: 77.215630%
Total loss: 5.431836
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  35
Train -
Class accuracy is: 82.915787%
No obj accuracy is: 98.022110%
Obj accuracy is: 77.054306%
Total loss: 4.051095
Validation -
Class accuracy is: 82.729340%
No obj accuracy is: 97.910042%
Obj accuracy is: 77.456772%
Total loss: 5.308744
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  36
Train -
Class accuracy is: 83.271507%
No obj accuracy is: 98.063332%
Obj accuracy is: 77.344788%
Total loss: 3.999158
Validation -
Class accuracy is: 83.911537%
No obj accuracy is: 97.843346%
Obj accuracy is: 78.228966%
Total loss: 5.157840
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  37
Train -
Class accuracy is: 83.654503%
No obj accuracy is: 98.052826%
Obj accuracy is: 77.437607%
Total loss: 3.935004
Validation -
Class accuracy is: 83.446297%
No obj accuracy is: 97.924225%
Obj accuracy is: 77.840515%
Total loss: 5.665500
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  38
Train -
Class accuracy is: 83.677711%
No obj accuracy is: 98.045784%
Obj accuracy is: 77.409363%
Total loss: 3.930660
Validation -
Class accuracy is: 83.283028%
No obj accuracy is: 97.952309%
Obj accuracy is: 77.489342%
Total loss: 5.863686
Creating checkpoint...
Validation: 0it [00:00, ?it/s]

Epoch  39
Train -
Class accuracy is: 83.752563%
No obj accuracy is: 98.055817%
Obj accuracy is: 77.487839%
Total loss: 3.922375
Validation -
Class accuracy is: 83.376297%
No obj accuracy is: 97.966339%
Obj accuracy is: 77.452858%
Total loss: 5.646774
Creating checkpoint...
```
