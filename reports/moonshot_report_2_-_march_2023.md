This month's work has been focused on finding and checking different datasets to train a future AI on. 

Here is a list of useful datasets I found:

- Instrument Recognition in Musical Audio Signals (IRMAS) dataset:
  - [https://www.upf.edu/web/mtg/irmas](https://www.upf.edu/web/mtg/irmas)
  - [https://zenodo.org/record/1290750](https://zenodo.org/record/1290750)
- Good-sounds.org dataset
  - [https://www.upf.edu/web/mtg/good-sounds](https://www.upf.edu/web/mtg/good-sounds)
  - [https://zenodo.org/record/4588740](https://zenodo.org/record/4588740)
- Mixed sounds from Youtube
  - [https://github.com/qiuqiangkong/audioset_tagging_cnn#1-download-dataset](https://github.com/qiuqiangkong/audioset_tagging_cnn#1-download-dataset)
  - Note: This is a general-purpose dataset. I will have to write a script to filter the sounds I want from [this list](http://storage.googleapis.com/us_audioset/youtube_corpus/v1/csv/class_labels_indices.csv).
- Synthesized Lakh (Slakh) Dataset
  - [http://www.slakh.com/](http://www.slakh.com/)
- University of Iowa
  - [https://theremin.music.uiowa.edu/MISPost2012Intro.html](https://theremin.music.uiowa.edu/MISPost2012Intro.html)

I may not end up using all of them --at least not in the beginning-- considering some have multiple instruments playing simultaneously, and most importantly, considering the size of the dataset.

The diversity in the dataset structures and formats will require me to write some converting scripts to normalize all those data.

Those will be reported in my functional specifications that will be pushed later on.

On the technical decisions that should be made within the next two months:

I need to find out the best range for the spectrograms (min and max frequencies) as well as the duration of the samples I will be working with.

I also need to choose whether to put money into an AI training service or to try and complete this project for free, and based on this decision which one to go for.