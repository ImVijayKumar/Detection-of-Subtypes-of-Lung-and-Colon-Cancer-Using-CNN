# Detection-of-Subtypes-of-Lung-and-Colon-Cancer-Using-CNN
## INTRODUCTION
The growth and spread of the body's abnormal cells
out of control is a characteristic shared by a group of
illnesses collectively referred to as cancer. The
ability of these cells to spread to other areas of the
body through the lymphatic or circulatory systems is
known as metastasis.
Lung and colon cancer come in a variety of forms,
each with special traits and methods of therapy.
Under a microscope, lung cancer may be generally
classified into two separate types based on how the
cancer cells appear: Non-small cell lung cancer
(NSCLC) accounts for the greater percentage of lung
cancer cases (85%). Adenocarcinoma, squamous
cell carcinoma, and giant cell carcinoma are among
the subtypes of NSCLC that can be further
subdivided.
Additionally, colon cancer can be categorized
according to the kind of cell that gives rise to it: 1.
Adenocarcinoma: This is the most common kind of
colon cancer, accounting for around 95% of cases.
Adenocarcinomas arise from the glandular cells
lining the inner surface of the colon.
2. Carcinoid tumors: These are an uncommon kind
of colon cancer that start in the colon's hormoneproducing cells.
A patient may get chemotherapy, radiation therapy,
immunotherapy, targeted therapy, or other
treatments for cancer, depending on the kind and
stage of the disease. As early identification and
treatment can improve the chance of recovery and
survival, routine screenings and check-ups are
essential to the prevention and management of
cancer.

Characterizing histopathological imaging data of
many cancer kinds, such as skin, breast, lung, colon,
and colorectal cancer, has garnered significant
attention.
There are several applications for ML, DL, and TL
in the detection of lung and colon cancer.
1. Using the ML technique to detect lung and colon
cancer: Masood et al. (2021) proposed an ML
method based on DL that analyzed pathological
pictures of lung and colon cancers to identify five
distinct tissue types. Following feature extraction
using the 2D Fourier and 2D Wavelet (2D FW)
methods, they merged the features and used them to
train a CNN model. The findings showed that the
recommended design was the most accurate in
identifying cancerous tissues, with a 96.33 percent
rate.
2. Using CAD to detect lung and colon cancer:
(Nishiio et al., 2021) described an automated CAD
system for classifying pictures of lung tissue
histopathology. They evaluated eight machine
learning methods on two datasets, including both
traditional texture analysis (TA) and homologybased image processing (HI) to extract visual
characteristics. The CAD system with HI
outperformed the TA system in both datasets. They
came to the conclusion that HI was far more effective
for CAD systems than TA and that this may lead to
the development of an accurate CAD system for lung
tissues. Moreover, (Shandilya and Nayak) created a
CAD technique in 2022 for categorizing lung tissue
histology pictures. They used a collection of
histological pictures of lung tissue that was made
accessible to the public for the development and
validation of CAD. To extract features from the
picture, multiscale processing was applied.
## METHODOLOGY
1. Data Collection: This stage involves gathering
from several sources the pertinent medical pictures
of the colon and lung. These pictures may be from a
colonoscopy, an MRI, or a CT scan.
2. Data Pre-processing: To eliminate any noise or
artifacts, the gathered photos are pre-processed.
After that, the pictures are standardized and scaled to
a standard size in order to feed them into the CNN
algorithm.
3. CNN Model Training: The pre-processed pictures
are used to train a CNN model.
Multiple convolutional layers in the model learn
attributes from the photos, and then fully connected
layers categorize the images as either malignant or
non-cancerous.
4. Model Testing: The Trained CNN model is then
examined using another set of pictures that weren't
utilized to teach the example. The model's
performance is assessed using many measures, such
as ROC, specificity, accuracy, and sensitivity bend.
5. Interpretation: After obtaining the model tested
and taught, the outcomes are analyzed to determine
the effectiveness of the suggested approach.
Moreover, Modifications or advancements can be
modified the model in light of the outcomes. It's
critical to remember that the particulars of each stage
may vary. Based on the specific dataset and research
objectives. As an example, the CNN model
construction and data enhancement techniques, and
choosing the hyperparameter can all have a
substantial impact on the model's execution. To
generate precise and reliable outcomes, it is essential
to appropriately schedule and execute each stage of
the method.
## SYSTEM IMPLEMENTATION
There are many processes involved in implementing
a Convolutional Neural Network (CNN) algorithmbased system for the diagnosis of lung and colon
cancer. This is a high-level summary of the
procedure:
1. Gather a sizable collection of medical photos
showing the colon and lungs, including samples that
are malignant and those that are not. The pictures are
accessible to the general public through databases or
medical facilities.
2. Pre-process the photos to make sure they are of the
same size and quality and to get rid of any noise or
artifacts that might skew the model's results.
3. Create more training pictures by transforming the
original photos in different ways, such rotating,
resizing, and flipping. This enhances the training
data's variety and strengthens the model's capacity
for generalization.
4. Make use of a CNN algorithm that is appropriate
for identifying lung and colon cancer. To determine
the ideal setup, this may entail testing with various
layers and hyperparameters.
5. Use the pre-processed and supplemented dataset
to train the CNN. To reduce the prediction error, this
entails feeding the CNN the pictures and modifying
the model's parameters.
6. Test the trained CNN's sensitivity, specificity, and
accuracy in identifying malignant areas using an
independent set of test pictures.
7. Include the CNN model that has been trained into
a software program that can receive fresh medical
pictures and produce a forecast of whether the
picture shows a colon or lung in good condition or
has cancerous regions.
8. Install the system in a clinical environment and
track its effectiveness over time to make sure it is
accurate and dependable in supporting the
identification and management of colon and lung
cancer.
## RESULTS
![image](https://github.com/imvijaykumar/Detection-of-Subtypes-of-Lung-and-Colon-Cancer-Using-CNN/assets/142383380/9a3c4fff-e5f2-425b-b014-1aae2ac4a1b4)
![image](https://github.com/imvijaykumar/Detection-of-Subtypes-of-Lung-and-Colon-Cancer-Using-CNN/assets/142383380/1f7742ba-230f-4345-b56a-8097cfba1527)
![image](https://github.com/imvijaykumar/Detection-of-Subtypes-of-Lung-and-Colon-Cancer-Using-CNN/assets/142383380/93f253f0-d731-4f1d-8f14-7ed1dc917a3f)
![image](https://github.com/imvijaykumar/Detection-of-Subtypes-of-Lung-and-Colon-Cancer-Using-CNN/assets/142383380/3fb12cce-6e27-4e86-986f-e6ea9ecb76f1)
![image](https://github.com/imvijaykumar/Detection-of-Subtypes-of-Lung-and-Colon-Cancer-Using-CNN/assets/142383380/744eb715-97b0-435f-9ff4-fbdad2823653)
![image](https://github.com/imvijaykumar/Detection-of-Subtypes-of-Lung-and-Colon-Cancer-Using-CNN/assets/142383380/4a518200-20f4-4135-a08b-cbae5fc842d5)
## CONCLUSION
To sum up, CNN-based algorithms for the
identification of lung and colon cancer have shown
promising results in accurately identifying cancerous
regions in medical images. These technologies have
the potential to significantly improve cancer diagnosis
and treatment results because they can detect cancer
early, reduce the need for unnecessary biopsies, and
raise the accuracy of diagnoses. However, there are a
number of limitations that limit the effectiveness of
these systems, including the likelihood of false
positives and false negatives, interpretability concerns,
and dependence on high-quality data. CNN-based lung
and colon cancer detection systems should be used in
conjunction with other diagnostic tools and by trained
medical professionals to provide a precise and reliable
cancer diagnosis.
Future advancements and integration of CNN-based
lung and colon cancer detection systems into clinical
practice are highly promising. As medical image
collections grow, we should expect these systems to
become more accurate. Additionally, advancements in
CNN designs and training techniques should make it
possible for these systems to be integrated with other
diagnostic tools for personalized treatment.
