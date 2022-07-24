## MRI dataset analysis and Model building

Magnetic resonance imaging(MRI) dataset contains data images of brains of humans that are used to classify whether a person is having Brain-Feature-Loss.

* The dataset contains 2060 images (size 6 gb) and a csv file having the labels.
* The images are in nii.gz format 
* And they are 3D.

## Libraries

pip install nibabel

nibabel :
This package provides read +/- write access to some common medical and neuroimaging file formats,
including: ANALYZE (plain, SPM99, SPM2 and later), GIFTI, NIfTI1, NIfTI2, CIFTI-2, MINC1, MINC2,
AFNI BRIK/HEAD, MGH and ECAT as well as Philips PAR/REC. We can read and write FreeSurfer geometry, 
annotation and morphometry files. There is some very limited support for DICOM. 
NiBabel is the successor of PyNIfTI.

The various image format classes give full or selective access to header (meta) information and
access to the image data is made available via NumPy arrays.

## Preprocessing the data

* The data should be resized (.resize from cv2)
* Plot the images using imshow
* data_analysis.ipynb for analyzing and pre-processing 

## Model Building

* Build the model using the pre-trained model VGG16
* model.ipynb for model building.
