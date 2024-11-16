# ABSTRACT 
Alzheimer’s disease is a neurodegenerative disorder that affects aging human population. It causes progressive degeneration of the nervous system, affecting the cognitive ability of human brain. 
The disorder causes the growth of amyloid plaques and tau tangles to abnormal levels due to excessive synthesis of the constituent proteins. This manifests itself as memory loss, vision loss and 
overall cognitive impairment leaving the subject dependent on external help for conduct of daily life. The disease is projected to affect a considerable proportion of population in the future. 
In the context of its wide-ranging effects on broader health system, it is imperative to develop sophisticated methods for early detection and diagnosis of Alzheimer’s disease. 
This can help to delay the onset of the disease. Over the past decade, neuroimaging data from Magnetic Resonance Imaging (MRI) scans have been increasingly used in the study of 
the brain pathology related to the birth and growth of AD. In the wake of advanced machine learning techniques, recent studies have employed machine learning for detection and classification of AD. 
Further, deep learning models have also been increasingly employed with varying degree of success. This thesis presents a novel hybrid approach for early detection and classification of AD using structural Magnetic Resonance Imaging (sMRI). 
Our model employs a unique combination of classical machine learning and deep learning approaches to optimize precision and accuracy of the intelligent detection and classification. 
The hybrid approach also helps overcome shortcomings of individual approaches regarding computational limitations. The approach combines ML and convolutional neural networks (CNN) 
where we fuse the image features extracted using classical machine learning techniques with features extracted by a convolutional neural network, before feeding them to classifier. 
We used a single most widely available modality i.e. sMRI. Our approach advantageously uses processed MRI scans and the extracted features to yield more information. 
The segmentation of cortical and subcortical regions through our framework helps in breaking spurious correlations in training data, resulting in better generalization. 
Our approach surpassed multi-modal machine learning algorithms in performance parameters of accuracy, precision, and F1 score. It is pertinent to note that the approach achieved this using only a single modality. 
Further, the results yielded by the hybrid approach beat Deep Learning models with better performance on validation data sets. To the best of our knowledge, our results in both AD versus NC and sMCI versus pMCI paradigms 
defeat the state-of-the-art of the field. Within the NC versus AD paradigm the model we developed achieved 91.84% accuracy on test data. We achieved an accuracy of more than 93% in validation dataset. 
The model achieved significant improvements in other parameters such as precision and F1 score. It is pertinent to note that the model was trained and tested under two paradigms, 
namely NC versus AD and sMCI versus pMCI. These reflect the two binary classifications employed to assess the development of the disease by our model. We conclude in a nutshell 
the proposed hybrid approach can help bypass bottlenecks of the classical ML and DL techniques and reap better results.
