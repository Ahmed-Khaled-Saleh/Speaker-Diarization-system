# Speaker Diarization system 

## Description

Diarization is the first step to solving audio transcription, which could hep us run different kinds of anlysis on the text generated. 


- What problem does it solve?
    -  To know who is talking when in a group of speakers and take some insights about him/her.
- Classification and Clustering?
    - After Diarizing the input Audio, we appy different classification and clustering techniques like the one learned in the course.

## Table of Contents


- [How to run the experiment](#How_to_run_the_experiment)
- [Used liberarys](#used)
- [Credits](#credits)


## How to run the experiment

Just Run all the notebook (warning: it takes time, almost half a hour). Use google colab to run the experiment on a run time of type GPU. If you intend to use it locally, you shoould adjust the paths of the files and have a good GPU running.

## Used liberaries

Those are the libraries that are installed on the Notebook.

    ```
    torch==1.11.0
    torchvision==0.12.0
    torchaudio==0.11.0
    torchtext==0.12.0
    speechbrain==0.5.12
    pyannote.audio
    pytube
    pydub
    pyLDAvis
    gensim
    nltk
    sklearn
    Numpy
    pandas
    matplotlib
    scipy
    ```

## Credits
- https://pyldavis.readthedocs.io/en/latest/readme.html
- https://ai.facebook.com/blog/wav2vec-20-learning-the-structure-of-speech-from-raw-audio/
- https://pyannote.github.io/



