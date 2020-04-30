# Dogs breed classification

This [dataset](https://www.kaggle.com/jessicali9530/stanford-dogs-dataset) contains images of 
120 breeds of dogs from around the world. Total number of images is 20,580.  
  
---
The prediction model consist of pre-trained MobileNetV3 model, 2 extra inception blocks and 1 short
connection. That's how the model looks like: 

![Model scheme](https://raw.githubusercontent.com/Yoskutik/StanfordDogsCV/master/Model.png)

---

The model is saved in `best_model.h5` file.  
Test accuracy of the model is 0.946, top 2 accuracy is 0.9764
