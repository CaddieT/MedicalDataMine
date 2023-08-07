# MedicalDataMine
The project provides the predicted results of open-source medical image datasets using state-of-the-art models to improve the efficiency of secondary annotations or directly use for researching.
  
## About The Pretrained Model
The X-ray chest model that detects 65 chest charactors or deseases was trained on more than 1 million images. The performance of main class as follow:
|Label|ROC|Label|ROC|
|----|----|----|----|
|Tuberculosis|0.996|Nodule|0.940|
|Pneumonia|0.970|Calcification|0.985|
|Fibroproliferative|0.966|Pleural thickening|0.964|
|Aortic Sclerosis|0.991|Rib Fractures|0.962|
|Pleural Effusion|0.982|Fibrosis|0.955|   

## Benefits&Efficiency
   
## Example Images

## Supported Dataset
[NIH Chest X-ray Dataset](https://nihcc.app.box.com/v/ChestXray-NIHCC)
[CheXpert Chest X-Ray Dataset](https://stanfordmlgroup.github.io/competitions/chexpert/)
[MIMIC-CXR Dataset](https://mimic.mit.edu/docs/iii/about/)
[OpenI: Chest X-ray Database](https://openi.nlm.nih.gov/faq)
[JSRT Chest X-ray Dataset](http://db.jsrt.or.jp/eng.php)

## Usage
If you want complete image labels, use follow steps:
First, download the labels throug [Amazon](https://www.amazon.com/?tag=amazusnavi-20&hvadid=616931945677&hvpos=&hvnetw=g&hvrand=9743093908080432574&hvpone=&hvptwo=&hvqmt=e&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=21176&hvtargid=kwd-10573980&ref=pd_sl_7j18redljs_e&hydadcr=28883_14649097) .
Second, download the image dataset you wanted from upper supported dataset.
Third, go to [LabelMe](https://github.com/wkentaro/labelme/tree/v4.1.4) repository to download V3.16.1-V4.1.4 edition source to build your label tool.
Fourth, move all you want to label or view images to one folder as the image directory for LableMe, and unzip the downloaded labels as image labels directory. Then you would view and check or modify the image labels.
