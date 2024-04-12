# TTS - VLSP 2021: The NAVI’s Text-To-Speech System for Vietnamese

**Abstract**: The Association for Vietnamese Language and Speech Processing (VLSP) has organized
a series of workshops intending to bring together researchers and professionals working in NLP and
attempt a synthesis of research in the Vietnamese language. One of the shared tasks held at the eighth
workshop is TTS [14] using a dataset that only consists of spontaneous audio. This poses a challenge
for current TTS models since they only perform well constructing reading-style speech (e.g,
audiobook). Not only that, the quality of the audio provided by the dataset has a huge impact on the
performance of the model. Specifically, samples with noisy backgrounds or with multiple voices
speaking at the same time will deteriorate the performance of our model. In this paper, we describe
our approach to tackle this problem: we first preprocess the training data then use it to train a
FastSpeech2 [10] acoustic model with some replacements in the external aligner model, finally we
use HiFiGAN [4] vocoder to construct the waveform. According to the official evaluation of VLSP
2021 competition in the TTS task, our approach achieves 3.729 in-domain MOS, 3.557 out-ofdomain MOS, and 79.70% SUS score. Audio samples are available at https://navi-tts.github.io/.
Keywords: VLSP-2021, Spontaneous, Text-to-speech.

# Paper
[TTS - VLSP 2021: The NAVI’s Text-To-Speech System for Vietnamese](https://jcsce.vnu.edu.vn/index.php/jcsce/article/view/347)
