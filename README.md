This work presents a novel approach utilizing deep learning
architectures to construct an emotion-based music recommendation system. The proposed system employs Convolutional
Neural Networks (CNNs) in conjunction with OpenCV to
accurately capture and depict users’ real-time mood which is
classified into either of these seven distinct classes, namely
Angry, Sad, Happy, Neutral, Surprised, Disgusted, and Fear.
To facilitate music recommendations, a dataset is curated,
by training a neural network model using a dataset, named
song moods sourced from Kaggle which comprises of 660
songs with labeled mood information to classify a much larger
dataset of 150,000 songs obtained from the Spotify Dataset on
Kaggle. The classification process categorizes these songs into
four main mood classes: Calm, Energetic, Happy, and Sad and
stores them in our dataset with the classified mood label. In
order to personalize the music recommendations, the system
leverages the Spotify API to access users’ Spotify accounts. By
analyzing the user’s most recently visited playlist, the system
obtains valuable insights into their current musical preferences
and runs similarity measures such as cosine similarity to finally
curate a list of 20 songs for the user based on their current
mood as well as their recent music choices.
