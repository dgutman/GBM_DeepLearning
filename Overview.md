Welcome to the GBM_DeepLearning wiki!

This consists of various data sets and utilities to process GBM/Glioma images in NIFTI format

These images include a background image as well as a segmented version

Example page:
http://node15.cci.emory.edu/lzhan_dev/html_nii_image_viewer/


Data set contains:
T1 and T2 Images (these represent different contrast/protocols of the MRI)


Data organization:
Within the repository, there is a "data" directory, and within that a DJ_RECURATED directory

Each subject should have ONE image, and only one image directory (if more, it requires cleanup).  Within a subject directory, there is a subdirectory which corresponds to a single scan date.

Within a scan directory, there should be the BACKGROUND_IMAGES directory (the base image), and in the primary directory is the T1 and T2 MASK.

