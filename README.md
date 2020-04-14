# 🛑 Note: This model is still not reliable to use. It is just a research for now. 

To read Motivation and Goal behind this research go to this [Github link](https://github.com/ieee8023/covid-chestxray-dataset/blob/master/README.md).


# Model Result
![Model Accuracy](https://github.com/Thehunk1206/Covid-19-chest-X-ray/blob/master/model/modelAccuracy_100.png)

![Model Loss](https://github.com/Thehunk1206/Covid-19-chest-X-ray/blob/master/model/modelLoss_100.png)

# Deploying model
After the model was trained it was compressed into [tflite](https://www.tensorflow.org/lite/) model. After which it was 
deployed on [flutter](https://flutter.dev/) application.
## ScreenShots of Flutter application


# Dataset source 
- [Covid19](https://github.com/ieee8023/covid-chestxray-dataset).
- [pnemonia and normal X-ray](https://data.mendeley.com/datasets/rscbjbr9sj/2)
![ss1](Application/Application\ Screenshot/Screenshot_20200413-195927.png)



This repository will be updating as the dataset will grow more and more.
Any contribution would be appreciated.

## Citation

Paper availabe [here](https://arxiv.org/abs/2003.11597)


```
@article{cohen2020covid,
  title={COVID-19 image data collection},
  author={Joseph Paul Cohen and Paul Morrison and Lan Dao},
  journal={arXiv 2003.11597},
  url={https://github.com/ieee8023/covid-chestxray-dataset},
  year={2020}
}
```


