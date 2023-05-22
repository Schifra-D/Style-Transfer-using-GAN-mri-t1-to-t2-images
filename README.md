# Style-Transfer-using-GAN-mri-t1-to-t2-images
Misdiagnosis in the medical field is a very serious issue but it’s also uncomfortably common to occur. Imaging procedures in the medical field requires an expert radiologist’s opinion since interpreting them is not a simple binary process ( Normal or Abnormal). Even so, one radiologist may see something that another does not. This can lead to conflicting reports and make it difficult to effectively recommend treatment options to the patient.

One of the complicated tasks in medical imaging is to diagnose MRI(Magnetic Resonance Imaging). Sometimes to interpret the scan, the radiologist needs different variations of the imaging which can drastically enhance the accuracy of diagnosis by providing practitioners with a more comprehensive understanding.

But to have access to different imaging is difficult and expensive. With the help of deep learning, we can use style transfer to generate artificial MRI images of different contrast levels from existing MRI scans. This will help to provide a better diagnosis with the help of an additional image.

Here CycleGAN is used to translate the style of one MRI image to another, which will help in a better understanding of the scanned image. Using GANs we created T2 weighted images from T1 weighted MRI image and vice-versa.

NOTE: The T1 and T2 MRI Images included in the dataset are not related in any way since we have an unpaired dataset here.
