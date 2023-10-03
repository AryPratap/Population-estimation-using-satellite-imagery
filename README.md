# Population-estimation-using-satellite-imagery

## Getting Started
```
git clone https://github.com/AryPratap/Population-estimation-using-satellite-imagery.git
```
## Data Mining and Processing 
We have two datasets for the project: the Center for International Earth Science Information Networks
(CIESIN) US Census Summary Grids for 2010, and up to date 2017 Landsat 7 high-resolution imagery
available in the base of Google public access map. 
<br>
The US POP census was downloaded from the below source 
```
http://sedac.ciesin.columbia.edu/data/collection/usgrid
```
The data mining of satellite imagery was done through the earthengine-api, can be accessed here. 
```
https://github.com/google/earthengine-api
```
Futher, data pickling and processing files can be found in the Data processing folder. 
## Model training 
The task of population density estimation is framed as a problem of multiclass-classification, where we have divided different population density ranges into specific classes. Futher a state-of-art pretrained VGG16 CNN model was fine-tuned on our satellite images. <br>
____ refer this file for fine-tuning details and model results . 
