# Clothes Recommendation on DeepFashion Dataset

![Result](https://github.com/suman9868/Fashion-Recommendation-System-using-pretrained-ResNet-model/blob/master/visual_output.jpg)

![Result2](https://github.com/suman9868/Fashion-Recommendation-System-using-pretrained-ResNet-model/blob/master/visual_output2.jpg)

<br />
<hr>

**INTRODUCTION**
<br />
This Github repo presents a fashion recommendation system trained on the DeepFashion dataset. The DeepFashion dataset is one of the largest and richly annotated fashion datasets.
, which consists of 800k images.   
<hr>

**DATASET**
<br />
The DeepFashion dataset consists of 800K images which are further annotated with 1000 attributes and 50 categories. The feature labels are broadly divided into two parts i.e. clothing category and attributes category. The dress category consists of noun names e.g. "dress". The attribute category consists of a combination of adjectives e.g. "animal print". The experiment perform on top 5 classes which are as follows:
<ul>
  <li>Texture Attributes: Palm, color blocked, stripes, etc. </li>
  <li>Fabrics Attributes: Leather, tweed, etc. </li>
  <li>Fabrics Attributes: Leather, tweed, etc. </li>
  <li>Shape Attributes: Crop, Midi, etc. </li>
  <li>Part Attributes: Bow-F, Fringed-H, etc. </li>
  <li>Style Attributes: Mickey, baseball, etc. </li>
</ul>
<hr>

**METHODOLOGY**
![Methodology](https://github.com/suman9868/Fashion-Recommendation-System-using-pretrained-ResNet-model/blob/master/methodology.jpg)
<hr>

**CODE FILE DESCRIPTION**
<br />
The following ipynb file contains the code for preprocessing part done on the category, and five groups of attribute like <br />
texture, fabric, shape, part and style. <br />
<ul>
<li>Data_Preprocessing_Attribute_class_1_TEXTURE.ipynb </li>
<li>Data_Preprocessing_Attribute_class_2_FABRIC.ipynb </li>
<li>Data_Preprocessing_Attribute_class_3_SHAPE.ipynb </li>
<li>Data_Preprocessing_Attribute_class_4_PART.ipynb </li>
<li>Data_Preprocessing_Attribute_class_5_STYLE.ipynb </li>
<li>Data_Preprocessing_Category.ipynb </li>
</ul>
The following ipynb file contains the code for applying ResNet model on the category and five groups of attributes. All file <br />
includes data loading, ResNet implementation and training part and best model save. <br />
<ul>
<li>CF-Project_Attribute_Texture_balanced_resnet.ipynb </li>
<li>CF-Project_Attribute_Fabric_balanced_resnet.ipynb </li>
<li>CF-Project_Attribute_Shape_balanced_resnet.ipynb </li>
<li>CF-Project_Attribute_Part_balanced_resnet.ipynb </li>
<li>CF-Project_Attribute_Style_balanced_resnet.ipynb </li>
<li>CF-Project_Category_balanced_resnet.ipynb </li>
</ul>
The following ipynb file contain the code for all six model loading, taking input and for each input predicting the top 5 most <br /> 
suitable images using KNN. <br />
<ul>
<li>KNN-CF-Project.ipynb </li>
</ul>
<hr>

**RESULT**

![Result](https://github.com/suman9868/Fashion-Recommendation-System-using-pretrained-ResNet-model/blob/master/visual_output.jpg)

![Result2](https://github.com/suman9868/Fashion-Recommendation-System-using-pretrained-ResNet-model/blob/master/visual_output2.jpg)
