-- The Flickr 8k Audio Caption Corpus --

This data is distributed under the Creative Commons Attribution-ShareAlike (CC BY-SA) license.
 
If you use this data, please cite

D. Harwath and J. Glass, "Deep Multimodal Semantic Embeddings for Speech and Images," 2015 IEEE Automatic Speech Recognition and Understanding Workshop, pp. 237-244, Scottsdale, Arizona, USA, December 2015

as well as the original Flickr 8k text caption corpus:

M. Hodosh, P. Young and J. Hockenmaier (2013) "Framing Image Description as a Ranking Task: Data, Models and Evaluation Metrics", Journal of Artifical Intellegence Research, Volume 47, pages 853-899
http://www.jair.org/papers/paper3994.html

You can download the original Flickr 8k corpus of text captions here:
http://nlp.cs.illinois.edu/HockenmaierGroup/Framing_Image_Description/KCCA.html

Here is a brief description of what is included in the Flickr 8k audio data:

The wavs/ directory contains 40,000 spoken audio captions in .wav audio format, one for each caption included in the train, dev, and test splits in the original Flickr 8k corpus (as defined by the files Flickr_8k.trainImages.txt, Flickr_8k.devImages.txt, and Flickr_8k.testImages.txt)

The audio is sampled at 16000 Hz with 16-bit depth, and stored in Microsoft WAVE audio format

The file wav2capt.txt contains a mapping from the .wav file names to the corresponding .jpg images as well as caption number. The .jpg file names and caption numbers can then be mapped to the caption text via the Flickr8k.token.txt file from the original Flickr 8k corpus.

The file wav2spk.txt contains a mapping from the .wav file names to its speaker. Each unique speaker is numbered consecutively from 1 to 183 (the total number of unique speakers).

---

Flickr 1d modifications:

The above describes the full Flickr 8k audio caption corpus.
The Flickr 1d dataset is a small subset of only 10 images of the full Flickr 8k corpus.
Therefore, in this repository, you'll only find the 50 .wav files corresponding to those 10 images. 
