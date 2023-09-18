# SoundSpray Project (with pretrained CLAP Model)
This project goes beyond CV and NLP into the realm of Audio. We collected sound data, constructed our own dataset, and used the CLAP model to create a genre classification model for drum instruments. We utilized the one-shot approach of the LAION-AI CLAP model for performing classification.

## Purpose
The SoundSpray project is based on the CLAP model and aims to classify specific musical instruments within drum sounds.

## Dataset
We have collected and labeled a dataset consisting of 1440 text-wave pairs of drum sounds. This dataset was meticulously curated for training and evaluation.

## Results
Our model excels in the classification of various drum instruments, including clap, hihat, snare, kick, and cymbal. When evaluated on our test set, it achieved an impressive accuracy of 0.80.

## Reference
CLAP: https://github.com/LAION-AI/CLAP

![workflow](https://github.com/springwater00/Aiffel/blob/main/Aiffelthon/data/workflow.PNG)
![basedmodel](https://github.com/springwater00/Aiffel/blob/main/Aiffelthon/data/basemodel.PNG)
![result](https://github.com/springwater00/Aiffel/blob/main/Aiffelthon/data/Result.PNG)
