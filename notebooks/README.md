
## ✅ Description
This is a STT which was made as an assignment for my Programming course from MSc Voice Technology at Rijksuniversiteit Groningen/Campus Fryslân.

The data is my 105 English recordings in [Common Voice](https://commonvoice.mozilla.org/en) (takeout_442_metadata.txt and takeout_442_pt_0.zip).


## ✅ What did I do?
How I first did it was just like the notebook but then hit the stone and realized the link will be expired after some time so I just downloaded my data and uploaded it here so I can train my STT easier. Take a look at "Speech-to-Text model for Golshid's voice" notebook to get a better idea and understand what I did.

| Notebook title | Language(s) | Link to Colab |
|----------------|---------------|-------------|
| Create a custom Speech-to-Text model for your voice (the original and not my notebook) | English | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/coqui-ai/STT/blob/main/notebooks/train_personal_model_with_common_voice.ipynb) |
| Speech-to-Text model for Golshid's voice | English | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/Golesheed/f4160b891d7d1ec22fac89bc05a3f4fc/golshid-s-personal-model-with-common-voice.ipynb?authuser=1) |

## ✅ Results
The whole training and testing will take up to an hour. The results are bellow:
| Test number | WER | CER |
|----------------|---------------|-------------|
Test 1 |  0.234921 | 0.099295 |
Test 2 |  0.209524 | 0.092784 |

And from what I expected it is really good and hope I can help improving this model in the future.
