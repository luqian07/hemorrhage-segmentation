# Brain CT Image Hemorrhage Segmentation

# Introduction
Intracranial hemorrhage (ICH), also known as cerebral bleed, is caused by bleeding within the brain tissue itself or between the brain tissue and skull. It is the second common cause of stroke, and it is a potential life-threatening medical emergency. There are five different types of ICH based on the main areas where the bleeding occurs: either between the skull and brain tissue, or within the brain tissue. Three types of ICH can occur between the skull and brain tissue: Epidural hemorrhage, which happens between the skull bone and the dura mater; Subdural hemorrhage, which happens between the dura mater and the arachnoid membrane; Subarachnoid hemorrhage, which happens between the arachnoid membrane and the pia mater. Additionally, two types of ICH can occur inside the brain tissue: Intracerebral hemorrhage, which occurs anywhere inside the brain tissue itself; and Intraventricular hemorrhage, which occurs in the brain’s ventricles. The following figure is an example of brain CT scans of different types of ICH.

![Picture1](https://github.com/luqian07/hemorrhage-segmentation/assets/146892721/707d0862-f9cb-497e-8d73-d8cc8fffdc71)

When a patient is brought to the emergency room with a suspected intracranial hemorrhage, Computed Tomography (CT)scan is typically used to help doctors detect the bleeding and make diagnosis for optimal treatments. However, the diagnosis is complicated since it requires an accurate and immediate identification of the medical images in urgent situations.In order to improve this process for effective treatment, three different machine learning models were performed, including two convolutional neural network (CNN) models and one decision tree model to classify different types of ICH from brain CT scans. In addition, another CNN model was built for segmentation of the bleeding from the brain CT images.
