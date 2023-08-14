# S13 Assignment - Notebook

## S13.ipynb
The notebook clones yolov3.git repo using -

```
!git clone https://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@github.com/piygr/yolov3.git
```

The repo has a models folder which contains the [YoloV3Lightning.py](https://github.com/piygr/yolov3/blob/main/models/YoloV3Lightning.py) file containing
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

## LRFinder Results
Picked max_lr value = **3.5E-04** for the One Cycle Policy Scheduler.

<img width="669" alt="Screenshot 2023-08-14 at 6 24 11 PM" src="https://github.com/piygr/yolov3/assets/135162847/2133c9d2-e1e5-4234-b994-bb310635ea00">

```
Sanity Checking: 0it [00:00, ?it/s]
Training: 0it [00:00, ?it/s]
Validation: 0it [00:00, ?it/s]
Epoch  0
Train -
Class accuracy is: 18.945129%
No obj accuracy is: 0.008543%
Obj accuracy is: 99.964752%
Total loss: 33.835102
Validation -
Class accuracy is: 35.842766%
No obj accuracy is: 0.067255%
Obj accuracy is: 99.771370%
Total loss: 23.140484
Creating checkpoint...

Epoch  1
Train -
Class accuracy is: 31.964359%
No obj accuracy is: 8.619146%
Obj accuracy is: 74.675957%
Total loss: 17.216675
Validation -
Class accuracy is: 37.944027%
No obj accuracy is: 23.687878%
Obj accuracy is: 41.975616%
Total loss: 14.293047
Creating checkpoint...

Epoch  2
Train -
Class accuracy is: 33.912487%
No obj accuracy is: 77.707642%
Obj accuracy is: 18.746780%
Total loss: 13.526443
Validation -
Class accuracy is: 40.501522%
No obj accuracy is: 99.149986%
Obj accuracy is: 3.455251%
Total loss: 12.797545
Creating checkpoint...

Epoch  3
Train -
Class accuracy is: 36.690193%
No obj accuracy is: 99.660309%
Obj accuracy is: 5.829345%
Total loss: 12.108984
Validation -
Class accuracy is: 44.896091%
No obj accuracy is: 99.911507%
Obj accuracy is: 3.538377%
Total loss: 11.464461
Creating checkpoint...

Epoch  4
Train -
Class accuracy is: 39.946945%
No obj accuracy is: 97.901718%
Obj accuracy is: 23.120291%
Total loss: 11.072896
Validation -
Class accuracy is: 50.238293%
No obj accuracy is: 98.397186%
Obj accuracy is: 21.055695%
Total loss: 10.315847
Creating checkpoint...

Epoch  5
Train -
Class accuracy is: 43.326199%
No obj accuracy is: 97.270912%
Obj accuracy is: 35.347736%
Total loss: 10.287346
Validation -
Class accuracy is: 48.506512%
No obj accuracy is: 98.666992%
Obj accuracy is: 24.915489%
Total loss: 9.706395
Creating checkpoint...

Epoch  6
Train -
Class accuracy is: 46.569199%
No obj accuracy is: 97.178749%
Obj accuracy is: 44.260895%
Total loss: 9.589930
Validation -
Class accuracy is: 50.900524%
No obj accuracy is: 99.038208%
Obj accuracy is: 23.638126%
Total loss: 9.993618
Creating checkpoint...

Epoch  7
Train -
Class accuracy is: 49.025406%
No obj accuracy is: 97.219353%
Obj accuracy is: 48.182659%
Total loss: 9.114598
Validation -
Class accuracy is: 49.201996%
No obj accuracy is: 98.801842%
Obj accuracy is: 27.461901%
Total loss: 10.391318
Creating checkpoint...

Epoch  8
Train -
Class accuracy is: 52.132339%
No obj accuracy is: 97.327385%
Obj accuracy is: 50.924610%
Total loss: 8.554110
Validation -
Class accuracy is: 56.614025%
No obj accuracy is: 98.374542%
Obj accuracy is: 41.748409%
Total loss: 8.989867
Creating checkpoint...

Epoch  9
Train -
Class accuracy is: 54.692245%
No obj accuracy is: 97.393356%
Obj accuracy is: 54.707615%
Total loss: 8.170681
Validation -
Class accuracy is: 60.005539%
No obj accuracy is: 98.390366%
Obj accuracy is: 43.945690%
Total loss: 8.123799
Creating checkpoint...

Epoch  10
Train -
Class accuracy is: 56.861275%
No obj accuracy is: 97.392143%
Obj accuracy is: 58.887577%
Total loss: 7.797760
Validation -
Class accuracy is: 66.769188%
No obj accuracy is: 98.334282%
Obj accuracy is: 53.945690%
Total loss: 7.230187
Creating checkpoint...

Epoch  11
Train -
Class accuracy is: 58.681904%
No obj accuracy is: 97.463356%
Obj accuracy is: 60.725975%
Total loss: 7.527331
Validation -
Class accuracy is: 67.666939%
No obj accuracy is: 98.101723%
Obj accuracy is: 54.887783%
Total loss: 7.105114
Creating checkpoint...

Epoch  12
Train -
Class accuracy is: 60.843945%
No obj accuracy is: 97.504692%
Obj accuracy is: 62.733425%
Total loss: 7.172102
Validation -
Class accuracy is: 71.457466%
No obj accuracy is: 98.397888%
Obj accuracy is: 56.708229%
Total loss: 6.370053
Creating checkpoint...

Epoch  13
Train -
Class accuracy is: 62.535049%
No obj accuracy is: 97.565117%
Obj accuracy is: 63.914181%
Total loss: 6.910800
Validation -
Class accuracy is: 69.052368%
No obj accuracy is: 98.025688%
Obj accuracy is: 58.162926%
Total loss: 7.224635
Creating checkpoint...

Epoch  14
Train -
Class accuracy is: 64.287857%
No obj accuracy is: 97.623047%
Obj accuracy is: 64.787788%
Total loss: 6.683444
Validation -
Class accuracy is: 73.779442%
No obj accuracy is: 98.652740%
Obj accuracy is: 56.345249%
Total loss: 5.947072
Creating checkpoint...

Epoch  15
Train -
Class accuracy is: 65.833260%
No obj accuracy is: 97.658043%
Obj accuracy is: 66.016243%
Total loss: 6.451904
Validation -
Class accuracy is: 73.424767%
No obj accuracy is: 98.730110%
Obj accuracy is: 53.990025%
Total loss: 6.534176
Creating checkpoint...

Epoch  16
Train -
Class accuracy is: 67.202629%
No obj accuracy is: 97.708702%
Obj accuracy is: 66.999443%
Total loss: 6.244505
Validation -
Class accuracy is: 75.098366%
No obj accuracy is: 98.483467%
Obj accuracy is: 60.889442%
Total loss: 5.822238
Creating checkpoint...

Epoch  17
Train -
Class accuracy is: 68.945305%
No obj accuracy is: 97.723724%
Obj accuracy is: 68.223854%
Total loss: 6.012008
Validation -
Class accuracy is: 77.168190%
No obj accuracy is: 98.306870%
Obj accuracy is: 63.829315%
Total loss: 5.596472
Creating checkpoint...

Epoch  18
Train -
Class accuracy is: 70.236412%
No obj accuracy is: 97.781975%
Obj accuracy is: 68.582306%
Total loss: 5.842261
Validation -
Class accuracy is: 78.783592%
No obj accuracy is: 98.697807%
Obj accuracy is: 64.020500%
Total loss: 5.249847
Creating checkpoint...

Epoch  19
Train -
Class accuracy is: 71.343445%
No obj accuracy is: 97.809563%
Obj accuracy is: 69.591805%
Total loss: 5.667368
Validation -
Class accuracy is: 79.129951%
No obj accuracy is: 98.730476%
Obj accuracy is: 62.945412%
Total loss: 5.233456
Creating checkpoint...

Epoch  20
Train -
Class accuracy is: 72.654793%
No obj accuracy is: 97.856544%
Obj accuracy is: 70.164673%
Total loss: 5.469507
Validation -
Class accuracy is: 81.928513%
No obj accuracy is: 98.591469%
Obj accuracy is: 66.561378%
Total loss: 4.831263
Creating checkpoint...

Epoch  21
Train -
Class accuracy is: 73.637077%
No obj accuracy is: 97.897049%
Obj accuracy is: 70.928040%
Total loss: 5.330171
Validation -
Class accuracy is: 81.817680%
No obj accuracy is: 98.774963%
Obj accuracy is: 65.971184%
Total loss: 4.821824
Creating checkpoint...

Epoch  22
Train -
Class accuracy is: 74.532204%
No obj accuracy is: 97.919060%
Obj accuracy is: 71.396454%
Total loss: 5.191181
Validation -
Class accuracy is: 82.391243%
No obj accuracy is: 98.815361%
Obj accuracy is: 66.070930%
Total loss: 4.702610
Creating checkpoint...

Epoch  23
Train -
Class accuracy is: 75.928787%
No obj accuracy is: 97.970978%
Obj accuracy is: 72.122513%
Total loss: 5.008260
Validation -
Class accuracy is: 84.258797%
No obj accuracy is: 98.520096%
Obj accuracy is: 70.263229%
Total loss: 4.480551
Creating checkpoint...

Epoch  24
Train -
Class accuracy is: 76.904701%
No obj accuracy is: 97.969872%
Obj accuracy is: 72.500916%
Total loss: 4.870728
Validation -
Class accuracy is: 84.607925%
No obj accuracy is: 98.882469%
Obj accuracy is: 66.586311%
Total loss: 4.506808
Creating checkpoint...

Epoch  25
Train -
Class accuracy is: 77.746544%
No obj accuracy is: 98.015266%
Obj accuracy is: 72.947395%
Total loss: 4.759869
Validation -
Class accuracy is: 84.743698%
No obj accuracy is: 98.893112%
Obj accuracy is: 67.013023%
Total loss: 4.318770
Creating checkpoint...

Epoch  26
Train -
Class accuracy is: 78.878998%
No obj accuracy is: 98.019516%
Obj accuracy is: 73.601463%
Total loss: 4.579243
Validation -
Class accuracy is: 86.198395%
No obj accuracy is: 98.898270%
Obj accuracy is: 67.913551%
Total loss: 4.209585
Creating checkpoint...

Epoch  27
Train -
Class accuracy is: 79.540077%
No obj accuracy is: 98.050880%
Obj accuracy is: 74.031143%
Total loss: 4.484564
Validation -
Class accuracy is: 85.757828%
No obj accuracy is: 98.805710%
Obj accuracy is: 68.667221%
Total loss: 4.174301
Creating checkpoint...

Epoch  28
Train -
Class accuracy is: 80.625534%
No obj accuracy is: 98.071960%
Obj accuracy is: 74.675598%
Total loss: 4.352511
Validation -
Class accuracy is: 86.497650%
No obj accuracy is: 98.939743%
Obj accuracy is: 68.282074%
Total loss: 4.054517
Creating checkpoint...

Epoch  29
Train -
Class accuracy is: 81.179619%
No obj accuracy is: 98.100800%
Obj accuracy is: 75.102493%
Total loss: 4.252120
Validation -
Class accuracy is: 87.193123%
No obj accuracy is: 98.987350%
Obj accuracy is: 71.177612%
Total loss: 3.932935
Creating checkpoint...

Epoch  30
Train -
Class accuracy is: 81.938133%
No obj accuracy is: 98.131790%
Obj accuracy is: 76.048561%
Total loss: 4.152327
Validation -
Class accuracy is: 87.927399%
No obj accuracy is: 98.897781%
Obj accuracy is: 73.530067%
Total loss: 3.848360
Creating checkpoint...

Epoch  31
Train -
Class accuracy is: 82.723114%
No obj accuracy is: 98.135361%
Obj accuracy is: 76.508636%
Total loss: 4.045562
Validation -
Class accuracy is: 87.683571%
No obj accuracy is: 98.979736%
Obj accuracy is: 73.560539%
Total loss: 3.744921
Creating checkpoint...

Epoch  32
Train -
Class accuracy is: 83.289658%
No obj accuracy is: 98.173592%
Obj accuracy is: 77.020874%
Total loss: 3.955193
Validation -
Class accuracy is: 88.359657%
No obj accuracy is: 98.963440%
Obj accuracy is: 73.577164%
Total loss: 3.737903
Creating checkpoint...

Epoch  33
Train -
Class accuracy is: 83.721634%
No obj accuracy is: 98.187485%
Obj accuracy is: 77.017494%
Total loss: 3.877588
Validation -
Class accuracy is: 88.379059%
No obj accuracy is: 98.987480%
Obj accuracy is: 73.845940%
Total loss: 3.671454
Creating checkpoint...

Epoch  34
Train -
Class accuracy is: 84.155746%
No obj accuracy is: 98.197189%
Obj accuracy is: 77.357529%
Total loss: 3.824658
Validation -
Class accuracy is: 88.966469%
No obj accuracy is: 98.936478%
Obj accuracy is: 75.259071%
Total loss: 3.621994
Creating checkpoint...

Epoch  35
Train -
Class accuracy is: 84.520805%
No obj accuracy is: 98.217369%
Obj accuracy is: 77.363945%
Total loss: 3.773572
Validation -
Class accuracy is: 88.728180%
No obj accuracy is: 98.993042%
Obj accuracy is: 74.400108%
Total loss: 3.620832
Creating checkpoint...

Epoch  36
Train -
Class accuracy is: 84.860680%
No obj accuracy is: 98.209663%
Obj accuracy is: 77.739563%
Total loss: 3.740484
Validation -
Class accuracy is: 88.963699%
No obj accuracy is: 99.033958%
Obj accuracy is: 74.009415%
Total loss: 3.584393
Creating checkpoint...

Epoch  37
Train -
Class accuracy is: 85.008575%
No obj accuracy is: 98.215355%
Obj accuracy is: 77.739891%
Total loss: 3.704787
Validation -
Class accuracy is: 89.005264%
No obj accuracy is: 99.033699%
Obj accuracy is: 73.812691%
Total loss: 3.612664
Creating checkpoint...

Epoch  38
Train -
Class accuracy is: 84.991638%
No obj accuracy is: 98.219391%
Obj accuracy is: 77.742172%
Total loss: 3.711228
Validation -
Class accuracy is: 89.190910%
No obj accuracy is: 99.026070%
Obj accuracy is: 74.142418%
Total loss: 3.596256
Creating checkpoint...

Epoch  39
Train -
Class accuracy is: 85.174393%
No obj accuracy is: 98.219826%
Obj accuracy is: 77.884247%
Total loss: 3.683274
Validation -
Class accuracy is: 89.135490%
No obj accuracy is: 99.021400%
Obj accuracy is: 74.308678%
Total loss: 3.590519
Creating checkpoint...
```
And achieved MAP as **0.510537326335907**

