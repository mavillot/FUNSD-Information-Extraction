# FUNSD-Information-Extraction

Forms are a widespread type of document used in lots of fields. They are an appropriate way to collect and communicate data. The demand in digitising forms and interpreting data is enormous.

In this repository we have focused on the task of **form understanding** from scanned documents. It can be defined as the process of automatically extracting information from a form, and it is usually approached by analysing both *textual contents* and *organisational structures*. This task remains a challenging task due to the diversity of
templates, structures, layouts, and formats that can greatly vary from one form to another.

The scarcity of works in this area is mainly based on the absence of datasets of forms due to the sensitive information included in these documents. Therefore,in 2019, FUNSD dataset was released. This is a dataset with 199 fully annotated images.

We will combine **computer vision** and **natural language processing** techniques. The computer vision techniques will take care of the detection task and the natural language processing techniques will take care of the text classification. We will also use some image processing and OCR which could be a solution for the localisation.

The difference between localisation and detection is that the localisation doesn't classify and the detection does.

So, 
- in the **Detection** directory we can find the models trained in IceVision: FasterRCNN, EfficientDet and FasterRCNN with a ResNests50 as backbone.
- in the **Classification** directory we will find the different models trained for text classification. We use the annotation's text labels in order to classify instead of doing OCR to the detections because OCR doesn't perform properly in the FUNSD dataset. 
- In the **Localisation** direction we will apply techniques of image processing in order to try other possibilities. However, the results we obtain are not the best.
