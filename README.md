# GRAPE-LEAF-DISEASE-PREDICTION

ABSTRACT

In farming, it is vital to recognize diseases of plant leaves and to improve the prediction quality of diseased plant leaves. Several laboratory-based techniques such as polymerase reaction decrease in agricultural output, and pesticide application, have really been identified for recognizing different diseases of plant leaves with human sight. Agriculture yield is improving every day as a result of current technological advancements. However, they are very time-intensive and costly for farmers. Deep Learning (DL) methods may help boost crop yields by identifying recently upgraded methodologies and diverse systematic patterns. To improve the reliability of the measurements, researchers focused on new methodologies in deep learning algorithms for diagnosing leaf diseases. Every model is essential and focuses on the path of deep learning applications as well as the challenges faced by farmers. The mobilenetv2 architecture is used in this study to determine how to diagnose diseases that affect leaves. This design is built on an inverted residual structure, with narrow bottleneck layers serving as the input and output of the residual block and extended representations as the inputs. Lightweight depth-wise convolutions are used in this architecture to select leaf characteristics in the intermediate expansion stage. This network has 53 layers in the very beginning. There are 32 filters in the first completely convolution layer, followed by 19 more bottleneck layers. To retain representational strength, non - linearities were eliminated in the narrow layers. The proposed method enables the decoupling of the input/output leaves from the transformation's expressiveness, offering a framework for additional study. The proposed model provides an accuracy of 95% in identifying the plant diseases.

Grape Diseases

Grapes are fruits originating from Europe and Western Asia. This fruit can be made into juice, dried into raisins or fermented into grapes and brandy. Besides grapes can also cure many diseases because it has medicinal properties. Grapes are an important fruit crop. The presence of diseases in grapes can result in losses for farmers. Identification of grape leaf disease is needed by farmers so that solutions can be found to avoid greater losses during harvest. Diseases of grape leaves such as powdery mildew and downy mildew can cause great losses. Diseases in plants are found in the leaves, fruits and on the stems of plants. Early detection of leaf diseases is a major challenge in agriculture.

Problem Definition

The problem of grape leaf disease is a significant concern in the agriculture industry, as it can lead to reduced crop yield, economic losses for farmers, and potential negative impacts on the overall grape production supply chain. Timely and accurate detection of grape leaf diseases is crucial for implementing effective disease management strategies. However, existing methods of disease identification often rely on manual inspection, which is labor-intensive, time-consuming, and may not be sufficiently precise. Additionally, there is a need for proactive measures to prevent the spread of diseases and minimize the use of chemical interventions. The problem can be further exacerbated by the increasing challenges posed by climate change and the emergence of new or more virulent strains of pathogens. The traditional methods of disease identification may struggle to keep pace with these dynamic environmental factors. Therefore, there is a clear need for an advanced and automated system that can predict and identify grape leaf diseases accurately and efficiently. Such a system could leverage modern technologies like machine learning, computer vision, and data analytics to analyze vast datasets of grape leaves and environmental conditions to predict the likelihood of disease occurrence. This would not only aid in early disease detection but also allow for the implementation of targeted and sustainable interventions, minimizing the use of pesticides and optimizing resource allocation in agriculture.
In summary, the problem at hand involves the need for a robust, automated grape leaf disease prediction system that addresses the limitations of current methods, enhances accuracy, and considers the dynamic nature of environmental factors influencing disease outbreaks. Developing such a system has the potential to revolutionize grape farming practices, ensuring better yields, reduced environmental impact, and improved overall sustainability in the agriculture sector.

REQUIREMENT ANALYSIS AND SPECIFICATION

Requirement Description
The hardware and software requirements for the grape leaf disease prediction system are as follows:

Hardware Specification

Computer with a processor speed of at least 2 GHz
RAM of at least 4 GB
Hard disk drive with at least 50 GB of free space
Digital camera or other imaging device

Software Specification

Image processing software (Colaboratory)
Machine learning framework, such as TensorFlow or scikit-learn

Results

The proposed model provides an accuracy of 98% in identifying the plant diseases. Comparison of base model architecture shows that MobilnetV2 gives the highest accuracy than ResNet50V2.

CONCLUSION AND FUTURE SCOPE

In conclusion, the implemented MobileNetV2-based grape disease prediction model offers a promising solution for early detection and management of diseases in grapevines. The positive outcomes of this study pave the way for further research, collaboration, and practical implementation in the agricultural sector, contributing to the advancement of precision farming practices. The proposed MobileNetV2-based model achieved a high degree of accuracy in predicting grape leaf diseases, with 98% accuracy on the validation set and 94.8% on the test set. This demonstrates the potential of MobileNetV2 for grape leaf disease prediction, particularly in mobile and embedded applications.
Incorporating additional data modalities, such as NIR images, hyperspectral images, and leaf texture data, could help the model learn more robust features. Developing a real-time system for early detection of grape leaf diseases in the field would be beneficial for grape growers, as it would allow them to take timely action to control diseases and prevent yield losses.
Exploring multi-task learning could enable the model to perform multiple tasks simultaneously, such as grape leaf disease prediction and grape leaf grading. This could improve the efficiency and accuracy of the system, as well as its usefulness for grape growers.


