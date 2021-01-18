# music_tagging

### Environment Setup 
To proceed to do data processing and model training, we have to install some packages - ffmpeg, libsoundfile, python packages - audioread and soundfile for feature extraction 

### MusiCNN Tagging 
[Musicnn](https://github.com/jordipons/musicnn) is a state of the art model for dataset magnatagatune.   [This notebook](https://github.com/catwhiskers/music_tagging/blob/main/02-musicnn.ipynb) demonstrates directly how to use MusiCNN to do tagging task 

### Using sotas of music tagging models 
[This work](Evaluation of CNN-based Automatic Music Tagging Models) implemented various models and performed evaluation over three open datasets. [This notebook](https://github.com/catwhiskers/music_tagging/blob/main/03-music-tagging-sotas.ipynb) demonstrates how to use the open sourced model and data to do transfer learning 

### Using Musicnn to do transfer learning 
[This notebook](https://github.com/catwhiskers/music_tagging/blob/main/04-musicnn-transfer-learning.ipynb) demonstrates how to use the open sourced [project](https://github.com/jordipons/sklearn-audio-transfer-learning) to do transfer learning over musicnn and other open sourced projects 

