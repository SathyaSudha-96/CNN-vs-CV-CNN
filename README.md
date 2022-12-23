# CNN-vs-CV-CNN
DKE Seminar SoSe2021


One of the most popular imaging techniques for detecting brain tumors is magnetic resonance imaging (MRI).
The anatomy, physiology, and metabolic activity of the lesion,as well as its hemodynamics, can all be studied using MRI.
To obtain the image, MRI is acquired in frequency space(k-space) and an inverse Fourier transform is applied. The
resultant image and the k-space are both complex-valued. For tumor detection, the magnitude of the resulting complex image
(which is then real-valued) is typically used. In recent years, deep learning algorithms in computer vision applications, such
as brain tumor segmentation and classification from MRIs, have demonstrated tremendous improvement. Convolutional
Neural Networks (CNN, real-valued) are commonly used to do classification and segmentation on magnitude images. The
other two complex-valued data-spaces (k-space and complex image) are, on the other hand, mostly unexplored. In those
dataspaces, a complex-valued Convolutional Neural Network (CV-CNN) can be utilized to do MRI classification directly.
The major goal of this study is to compare real-valued CNN performance with magnitude images to CV-CNN performance 
with complex images and CV-CNN performance with k-spac
