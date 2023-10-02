# Weighted-Ensemble-Approach-for-BrainTumor-MRI-images



## What is a brain tumor?
A brain tumor is a collection, or mass, of abnormal cells in your brain. Your skull, which encloses your brain, is very rigid. Any growth inside such a restricted space can cause problems. Brain tumors can be cancerous (malignant) or noncancerous (benign). When benign or malignant tumors grow, they can cause the pressure inside your skull to increase. This can cause brain damage, and it can be life-threatening.

Early detection and classification of brain tumors is an important research domain in the field of medical imaging and accordingly helps in selecting the most convenient treatment method to save patients life.

Example of Brain Tumor MRI images 
# Glioma
![Tr-gl_0012](https://github.com/IamAnubhav-08/Weighted-Ensemble-Approach-for-BrainTumor-MRI-images/assets/75220234/dd0a7edb-0ce1-469a-abda-5942c913b59a|width=100)

# Meningioma
![Tr-me_0023](https://github.com/IamAnubhav-08/Weighted-Ensemble-Approach-for-BrainTumor-MRI-images/assets/75220234/89d66332-aff3-47db-979d-5636872e2dec|width=100)

# No Tumor
![Tr-no_0039](https://github.com/IamAnubhav-08/Weighted-Ensemble-Approach-for-BrainTumor-MRI-images/assets/75220234/1220c080-fcfb-4efc-9192-f141b3c08d4d)

# Pituitary
![Tr-pi_0010](https://github.com/IamAnubhav-08/Weighted-Ensemble-Approach-for-BrainTumor-MRI-images/assets/75220234/1969bd95-b5f1-498f-84e4-b44f501b890f)

## An ensemble approach using 3 CNN models to classify the brain tumor MRI images

In this project, we try out different transfer learning models such as Resnet50, VGG16, VGG19, DenseNet121, and MobilenetV2.We find that 3 models reach above 97% test accuracy - VGG19, DenseNet121, and MobileNetV2. We deploy a **Grid Search** method to find the optimal weights that give us the best test accuracy.

The final test accuracy of the ensemble model is ***98.98%***

