# Lung-Cancer-Detection-using-CNN
Lung Cancer Detection using CNN



Using a data set of thousands of high-resolution lung scans provided by the National Cancer Institute, participants developed algorithms that accurately determine when lesions in the lungs are cancerous. This will dramatically reduce the false positive rate that plagues the current detection technology, get patients earlier access to life-saving interventions, and give radiologists more time to spend with their patients.
NOTE: due to data set usage restrictions, the data for this competition is no longer available for download.

In this dataset, you are given over a thousand low-dose CT images from high-risk patients in DICOM format. Each image contains a series with multiple axial slices of the chest cavity. Each image has a variable number of 2D slices, which can vary based on the machine taking the scan and patient.

The DICOM files have a header that contains the necessary information about the patient id, as well as scan parameters such as the slice thickness.

The task is to create an automated method capable of determining whether or not the patient will be diagnosed with lung cancer within one year of the date the scan was taken. The ground truth labels were confirmed by pathology diagnosis.

The images in this dataset come from many sources and will vary in quality. For example, older scans were imaged with less sophisticated equipment. You should expect the stage 2 data to be, on the whole, more recent and higher quality than the stage 1 data (generally having thinner slice thickness). Ideally, your algorithm should perform well across a range of image quality.
