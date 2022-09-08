## Brain Tumor Grade Classification in MR images using Deep Learning

#### - Master Thesis (732A64) at Linköpings Universitet (VT 22)

## Abstract

Brain tumors represent a diverse spectrum of cancer types which can induce grave complications and lead to poor life expectancy. Amongst the various brain tumor types, gliomas are primary brain tumors that compose about 30% of adult brain tumors. They are graded according to the World Health Organization into Grades 1 to 4 (G1-G4), where G4 is the highest grade with the highest malignancy and poor prognosis. Early diagnosis and classification of brain tumor grade is very important since it can improve the treatment procedure and (potentially) prolong a patient's life, since life expectancy largely depends on the level of malignancy and the tumor's histological characteristics. While clinicians have diagnostic tools they use as a gold standard, such as biopsies these are either invasive or costly. A widely used example of a non-invasive technique is magnetic resonance imaging, due to its ability to produce images with different soft-tissue contrast and high spatial resolution thanks to multiple imaging sequences. However, the examination of such images can be overwhelming for radiologists due to the overall large amount of data. Deep learning approaches, on the other hand, have shown great potential in brain tumor diagnosis and can assist radiologists in the decision-making process.

In this thesis, brain tumor grade classification in MR images is performed using deep learning. Two popular pre-trained CNN models (VGG-19, ResNet50) were employed using single MR modalities and combinations of them to classify gliomas into three grades. All models were trained using data augmentation on 2D images from the TCGA dataset, which consisted of 3D volumes from 142 anonymized patients. The models were evaluated based on accuracy, precision, recall, F1-score, AUC score, as well as the Wilcoxon Signed-Rank test to establish if one classifier was statistically significantly better than the other. Since deep learning models are typically 'black box' models and can be difficult to interpret by non-experts, Gradient-weighted Class Activation Mapping (Grad-CAM) was used in order to address model explainability. For single modalities, VGG-19 displayed the highest performance with a test accuracy of 77.86%, whilst for combinations of two and three modalities T1ce, FLAIR and T2, T1ce, FLAIR were the best performing ones for VGG-19 with a test accuracy of 74.48%, 75.78%, respectively. Statistical comparisons indicated that for single MR modalities and combinations of two MR modalities, there was not a statistically significant difference between the two classifiers, whilst for combination of three modalities, one model was better than the other. However, given the small size of the test population, these comparisons have low statistical power. The use of Grad-CAM for model explainability indicated that ResNet50 was able to localize the tumor region better than VGG-19.

Download my work: [Google Scholar](https://www.diva-portal.org/smash/record.jsf?pid=diva2:1674243)

Cite my work:

    Chatzitheodoridou, E. (2022). Brain Tumor Grade Classification in MR images using Deep Learning.
    

<img src="https://github.com/Eleftheria94/MScThesis/blob/main/img/workflow_1.png" width="1000" height="400">

<img src="https://github.com/Eleftheria94/MScThesis/blob/main/img/workflow_2.png" width="1000" height="600">

<img src="https://github.com/Eleftheria94/MScThesis/blob/main/img/workflow_3.png" width="900" height="300">

<img src="https://github.com/Eleftheria94/MScThesis/blob/main/img/workflow_4.png" width="1000" height="600">
