# HUMAN ACTIVITY RECOGNITION 🚶‍♀️🏃‍♀🧍‍♀️🤸‍♀️🏋️‍♂️🛌
Built a model that will extract the coordinates of the input image and predict the activity performed by the subject. 

Workflow includes 

🚶‍	Built own image dataset and preprocess it to make all images of the same format and size.

🚶‍	Perform segmentation where the images are divided  into   disjoint   segments   such   that   all   together   the  segmented  parts  form  the  original  image

🚶‍	The  segmentation step is followed by the motion tracking in which the basic idea is  to  detect  the  moving  objects  in  the  frame using Mediapipe BlazePose detector

🚶‍	Finally the obtained pose landmarks are converted to a representation suitable for the XGBoost classifier and classify them to recognize the activity.
