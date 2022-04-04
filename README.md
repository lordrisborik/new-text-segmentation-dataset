# new-text-segmentation-dataset
an alternative to choi's dataset

Choi dataset consists of 920 documents, created by /concatenation of 10 paragraphs randomly sampled from Brown corpus. The documents are distributed to different folders based on the number of sen-tences in each paragraph. This choi dataset is widly used for the evaluation of the performance of text segmentation models.

Here, I present a new dataset. In the dataset, the text is formatted as pandas dataframe which makes it easy to conduct dataframe operations on them. Namly, there are 2 columns, first column is a class of an article, a second column is a sentence of an article. The first column is helpful for feedback.

![image](https://user-images.githubusercontent.com/75815655/161476491-d252ee5c-efb4-449b-a87e-2c1d957d5124.png)

all Aticles are collected from World Wide Web news portals.

There are 4 folders. Folder one: merged-baseBall-Vaccine-1039, it has 1039 text, each text has baseBall realated sentences and Vaccine related sentences.

Folder two: merged-cinema_software-5025, it has 5025 text, each text has cinema realated sentences and software related sentences.

Folder three: merged-school-humanRt-airTrafic-1681, it has 1681 text, each text has school related sentences, human rights related sentences and air traffic related sentences.

Folder four: merged-fire-student-judiciary-railway-42119, it has 42119 text, each text has 4 diffirent contents: fire related, student related, judiciary related and railway related.

This text segmentation dataset provided as it is.
