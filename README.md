


# Python Summer Camp 2018 - CBPF

Simple MLP classifier for particles in a specific detector (data set from LEP MC simulations).

## ABSTRACT

Here I build a MLP classifier in order to look at detections made through 13 parameters and show if this particle is a electron, a muon, a tau, or a quark. It was build with Tensorflow/Keras and I also have compared with sklearn MLP method. 

## Results

ROC CURVE 
![ROC CURVE](https://user-images.githubusercontent.com/37218817/46362834-bcf5c080-c647-11e8-9452-85fa57503787.png)
```
AUC parameter : Electron:0.7999474887646882+-5.187713678145928e-10

AUC parameter : Muon:0.724573735598428+-3.602215918207911e-13

AUC parameter : Tau:0.7012339942923979+-3.2358704156963667e-13

AUC parameter : Quark:0.8192454954889842+-4.145071803506032e-10

```

## Authors

* **Yuri Muller Plumm Gomes** 


## Acknowledgments

* Thanks to Prof. Carsten for discussions, suggestions and for the MC simulations data used. 


