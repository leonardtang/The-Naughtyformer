# The Naughtyformer: A Transformer Understands Offensive Humor
Jokes are intentionally written to be funny, but
not all jokes are created the same. Some jokes
may be fit for a classroom of kindergarteners,
but others are best reserved for a more mature audience. While recent work has shown
impressive results on humor detection in text,
here we instead investigate the more nuanced
task of detecting humor subtypes, especially of
the less innocent variety. To that end, we introduce a novel jokes dataset filtered from Reddit
and solve the subtype classification task using
a finetuned Transformer dubbed the _Naughtyformer_. Moreover, we show that our model is
significantly better at detecting offensiveness
in jokes compared to state-of-the-art methods.

## Dataset
To train the Naughtyformer, we introduce a dataset
of 92,153 total jokes across categories of 1) Clean
Jokes, 2) Dark Jokes, and 3) Dirty Jokes. We also
include a fourth category, News, representing a
non-joke. 

The cleaned and post-processed data is found in `cleaned_data.csv`. The original Reddit is found in `raw_data/`.

## Model Checkpoint
Our DeBERTa checkpoint for the _Naughtyformer_ can be found [here](https://drive.google.com/file/d/15YMRcMT3JsXXKBmFx7jFfQS6om0Kfs-x/view?usp=sharing).

## Citation
If you find this useful in your research, please consider citing:
```
@article{tang2022naughtyformer,
  title={The Naughtyformer: A Transformer Understands Offensive Humor},
  author={Tang, Leonard and Cai, Alexander and Li, Steve and Wang, Jason},
  journal={arXiv preprint arXiv:2211.14369},
  year={2022}
}
```
