# HUMAN ACTIVITY RECOGNITION πΆββοΈπββπ§ββοΈπ€ΈββοΈποΈββοΈπ
Built a model that will extract the coordinates of the input image and predict the activity performed by the subject. 

Workflow includes 

πΆβ	Built own image dataset and preprocess it to make all images of the same format and size.

πΆβ	Perform segmentation where the images are divided  into   disjoint   segments   such   that   all   together   the  segmented  parts  form  the  original  image

πΆβ	The  segmentation step is followed by the motion tracking in which the basic idea is  to  detect  the  moving  objects  in  the  frame using Mediapipe BlazePose detector

πΆβ	Finally the obtained pose landmarks are converted to a representation suitable for the XGBoost classifier and classify them to recognize the activity.
