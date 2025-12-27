# Master-s-Thesis-A-Computed-Tomography-Atlas-of-Pulmonary-Nodules-for-Lung-Cancer-Screening

Abstract
Lung cancer is the leading cause of cancer-related mortality worldwide, and early detection
remains critical for improving survival rates. This thesis proposes an integrated framework for
automated construction of a probabilistic nodule atlas using low-dose computed tomography
(LDCT) data from the National Lung Screening Trial (NLST). The approach leverages two key
methodologies: Lesion Locator, a deep learning model for zero-shot segmentation, and the
Advanced Normalization Tools (ANTs) framework for inter-subject registration. Together,
these tools address challenges of anatomical variability, segmentation consistency, and inter-
patient comparison in LDCT screening data. LesionLocator was applied to the NLST dataset
to generate nodule masks. Subsequently, these masks were transformed into a standardized
anatomical space defined by a previously obtained lung template via Symmetric diffeomorphic
(SyN) non-linear registration. A nodule frequency map in the template space is then constructed
by accumulating the warped nodule masks. This map highlights high-density nodule regions in
the upper lobes and lung periphery, validating both the registration accuracy and the model’s
capacity to reproduce clinically known nodule distribution patterns in lung cancer screening.
This work establishes a reproducible computational workflow that generates objective spatial
priors for population-based analysis. The resulting atlas can serve as a foundational component
for future risk stratification tools and detection models, thereby complementing current
radiological assessment by automating high-throughput spatial measurements. Overall, this
thesis lays the groundwork for next-generation diagnostic systems that integrate machine
learning, medical imaging, and population-based analysis to enhance early cancer detection
and personalized patient care.
