### Anup Bagale

Biomedical engineer working on medical imaging, mostly brain MRI, in Python.

A lot of my projects start with a doubt about a good-looking result. Is the X-ray model
actually looking at the lungs? Does the heart disease model still work at another hospital?
How would you know a classifier got worse at a new site without labelling everything again?
I'd rather find out than report the number and move on.

**Research**

- [covid-xray-shortcut-learning](https://github.com/anupbagale/covid-xray-shortcut-learning):
  the classifier still scores 0.98 AUC with the lungs hidden. File metadata alone gets 0.99.
- [breast-ultrasound-performance-monitoring](https://github.com/anupbagale/breast-ultrasound-performance-monitoring):
  estimating sensitivity and PPV at a new hospital with few or no labels, on five datasets
  from five countries.
- [Heart_disease_prediction](https://github.com/anupbagale/Heart_disease_prediction):
  trained at one hospital, tested at three others. AUC drops from 0.90 to about 0.75, and
  the risk estimates are off by much more.
- [ssl-brain-parcellation](https://github.com/anupbagale/ssl-brain-parcellation):
  self-supervised pretraining for whole-brain parcellation. It helps most when only 10 to 25
  scans are labelled.
- [Whole-Brain-Segmentation](https://github.com/anupbagale/Whole-Brain-Segmentation):
  a 3D U-Net that reproduces 44 FreeSurfer structures in seconds instead of hours.
- [brain-age-prediction-ixi](https://github.com/anupbagale/brain-age-prediction-ixi):
  brain age from T1 MRI, with age-bias correction and a look at scanner effects.

**Teaching**

- [mri-recon-tutorial](https://github.com/anupbagale/mri-recon-tutorial):
  MRI reconstruction from k-space to compressed sensing and deep learning, all in Colab.
- One brain slice through [a CNN](https://github.com/anupbagale/cnn-one-image),
  [a ViT](https://github.com/anupbagale/how-vit-works),
  [self-supervised](https://github.com/anupbagale/how-self-supervised-learning-works) and
  [semi-supervised](https://github.com/anupbagale/how-semi-supervised-learning-works) learning,
  with the actual numbers at every step.
- [neural-networks-from-scratch](https://github.com/anupbagale/neural-networks-from-scratch) and
  [image-processing-from-scratch](https://github.com/anupbagale/image-processing-from-scratch):
  the classic algorithms, written out in NumPy.

**Small tools**

[segmentation-volumes](https://github.com/anupbagale/segmentation-volumes) ·
[segmentation-colormap](https://github.com/anupbagale/segmentation-colormap) ·
[csv-data-to-image](https://github.com/anupbagale/csv-data-to-image)

Python, PyTorch, MONAI, TensorFlow, scikit-learn, NumPy, nibabel

[Google Scholar](https://scholar.google.com/citations?user=oaV7zp8AAAAJ) ·
[LinkedIn](https://www.linkedin.com/in/anup-bagale-0708971a6)
