# CF_project: Clothes Recommendation using Category and Attribute Prediction Dataset(DeepFashion Dataset)
Methodology

![Methodology](https://github.com/suman9868/Fashion-Recommendation-System-using-pretrained-ResNet-model/blob/master/methodology.jpg)
The following ipynb file contains the code for preprocessing part done on the category, and five groups of attribute like <br />
texture, fabric, shape, part and style. <br /> 
-Data_Preprocessing_Attribute_class_1_TEXTURE.ipynb <br />
-Data_Preprocessing_Attribute_class_2_FABRIC.ipynb <br />
-Data_Preprocessing_Attribute_class_3_SHAPE.ipynb <br />
-Data_Preprocessing_Attribute_class_4_PART.ipynb <br />
-Data_Preprocessing_Attribute_class_5_STYLE.ipynb <br />
-Data_Preprocessing_Category.ipynb <br />

The following ipynb file contains the code for applying ResNet model on the category and five groups of attributes. All file <br />
includes data loading, ResNet implementation and training part and best model save. <br />
-CF-Project_Attribute_Texture_balanced_resnet.ipynb <br />
-CF-Project_Attribute_Fabric_balanced_resnet.ipynb <br />
-CF-Project_Attribute_Shape_balanced_resnet.ipynb <br />
-CF-Project_Attribute_Part_balanced_resnet.ipynb <br />
-CF-Project_Attribute_Style_balanced_resnet.ipynb <br />
-CF-Project_Category_balanced_resnet.ipynb <br />

The following ipynb file contain the code for all six model loading, taking input and for each input predicting the top 5 most <br /> 
suitable images using KNN. <br />
-KNN-CF-Project.ipynb <br />
