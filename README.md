# Baby-Cry-Prediction-
This repo contains scripts on how we can interpret baby cries based on donateacry-corpus. (https://github.com/gveres/donateacry-corpus) 
1) Infant emotion PREDICTION :
Our corpus contains five folders each of them represents an infant emotion class.
- **Belly_pain**   :   16 wav files.
- **Burping**        :    8 wav files.
- **Discomfort**  :    27 wav files.
- **Hungry**         :    382 wav files.
- **Tired**            :    24 wav files.

All of these sound files lasts between 6 and 7 seconds.
This data is not balanced and the Hungry class represents over 80% of the whole data.
Our goal is to maintain a balance between these classes by collecting data or by other data augmentation techniques for a better modeling.

We have used a deep learning approach to predict the sentiment. 
