# OCT-AND-EYE-FUNDUS-DATASET
Dataset of eye fundus and OCT images for the study of diabetic macular edema and diabetic retinophaty

The dataset is composed by 1548 Eye Fundus images and 1113 Macular Optical Coherence Tomography (OCT) images taken between 2015 and 2022, thanks to CONACYT CF-2019-1759 grant, PAPIIT IN 205420, IMO (Instituto Mexicano de Oftalmología), APEC (Asociación Para Evitar la Ceguera) and INDEREB (Instituto de Retina del Bajío).

In the file named ‘EYE FUNDUS.csv’, a list of the classification for all Eye Fundus images can be found.

The column named ‘DME’ specifies whether there is Diabetic Macular Edema (DME) or not in the corresponding image. If the value of the cell is 1, it means that DME has been diagnosed. On the contrary, a value of 0 corresponds to “no DME” diagnosis. As per the last count, the database contains 1053 Eye Fundus images with DME and 495 Eye Fundus images without DME.

The column named ‘DR’ provides information about Diabetic Retinopathy diagnosis and level for each image. The scales are the following: 0 corresponds to “no DR” diagnosis (398 Eye Fundus images); ‘NPDR’ corresponds to Non-Proliferative Diabetic Retinopathy (95 Eye Fundus images); ‘PDR’ corresponds to Proliferative Diabetic Retinopathy (52 Eye Fundus images), and finally, ‘-‘ means unknown classification.

The size for all Eye Fundus images is 1000x1000 pixels, and they all are in ‘.jpg’ format.

The ‘OCT.csv’ file contains detailed information for OCT images.

The column named ‘DME’ specifies whether Diabetic Macular Edema has been diagnosed. If the value of the cell is 1, it means that DME is present; on the contrary, a value of 0 corresponds to no DME present. As per the last count, the database contains 167 OCT images with EMD and 946 OCT images without EMD.

The column named ‘DR’ provides information about Diabetic Retinopathy diagnosis and degree for each image. Scales are as follows: 0 corresponds to no DR present (341 OCT images); ‘NPDR’ corresponds to Non-Proliferative Diabetic Retinopathy (119 OCT images); ‘PDR’ corresponds to Proliferative Diabetic Retinopathy (53 OCT images), and finally, ‘-‘ means unknown classification.

The size for all OCT images is 1408x573 pixels, and they all are in ‘.jpg’ format.



Both Eye Fundus and OCT images share the same nomenclature, including 4 different keys separated by the underscore symbol ‘_’:

1/ The first key refers to the patient. All images sharing the same number were taken from the same person.

2/ The second key provides information about the eyeball from which the sample was taken: ‘OD’ for right eyeball and ‘OI’ for left eyeball.

3/ The third key provides the sample category for each image: ‘o’ for OCT, and ‘f’ for Eye Fundus.

4/ The fourth and last key represents the sample number taken from the same object of study.



For example: ‘1221_OD_f_3’ corresponds to the 3rd sample picture of Eye Fundus image from the right eyeball of subject number 1221.

Diagnosis was established by retinal ophthalmologists.


To reference this dataset, cite as follows:
Hughes Cano, J. A., Olivares Pinto, U. & Thébault, S. “Dataset of Eye Fundus and OCT Images for the study of Diabetic Macular Edema and Diabetic Retinopathy”.
