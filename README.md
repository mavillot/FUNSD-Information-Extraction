# FUNSD-Information-Extraction

Forms are a widespread type of document used in lots of fields including administration, medicine, finance, or insurance. Forms are used as an appropriate
way to collect and communicate data following a structured format; and, nowadays, there is enormous demand in digitising forms, and interpreting the data
included in them. Forms are either provided under a born digital format (such as PDF, HTML, or documents included in web applications), or included
in a scanned image that comes from a form written or printed on a paper.

In this work, we have focused on the task of form understanding from scanned documents.

Form understanding can be defined as the process of automatically extracting information from a form, and it is usually approached by analysing
both textual contents and organisational structures. Form understanding on scanned documents remains as a challenging task due to the diversity of
templates, structures, layouts, and formats that can greatly vary from one form to another; and, also due to the quality of the scanned document images.

The scarcity of works in this area is mainly based on the absence of datasets of forms due to the sensitive information included in these documents. Therefore, a recent and important milestone in this area was the publication of the FUNSD dataset in 2019, which was the first publicly available dataset that was developed with form understanding purposes. This was a fully annotated dataset of image forms from noisy and old scanned documents.

The FUNSD Datatet is a freely available dataset for form understanding in noisy scanned documents. This dataset contains 199 fully annotated images of forms that vary widely with respect to their structure and appearance. The annotations of each image is encoded in a JSON file. Each form is represented as a list of semantic entities that are interlinked. A semantic entity is described by a unique identifier, a label (chosen from four categories: question, answer, header, or other), a bounding box with the position of the entity, a list of words, and a list of links with the relationships among entities
