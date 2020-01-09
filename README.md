# Audio to spectograms
This simple script provides audio data processing. It converts audio files to mfcc or filter bank spectograms.
Programing language used for this project was python 3.6.
## Algorithms

**MFCC**
In sound processing, the mel-frequency cepstrum (MFC) is a representation of the short-term power spectrum of a sound, based on a linear cosine transform of a log power spectrum on a nonlinear mel scale of frequency.

Mel-frequency cepstral coefficients (MFCCs) are coefficients that collectively make up an MFC.[1] They are derived from a type of cepstral representation of the audio clip (a nonlinear "spectrum-of-a-spectrum"). The difference between the cepstrum and the mel-frequency cepstrum is that in the MFC, the frequency bands are equally spaced on the mel scale, which approximates the human auditory system's response more closely than the linearly-spaced frequency bands used in the normal cepstrum.

**Filter Bank**
Filter bank is an array of band-pass filters that separates the input signal into multiple components, each one carrying a single frequency sub-band of the original signal. In digital signal processing, the term filter bank is also commonly applied to a bank of receivers. The difference is that receivers also down-convert the subbands to a low center frequency that can be re-sampled at a reduced rate. The same result can sometimes be achieved by undersampling the bandpass subbands.

Another application of filter banks is signal compression when some frequencies are more important than others. After decomposition, the important frequencies can be coded with a fine resolution. Small differences at these frequencies are significant and a coding scheme that preserves these differences must be used. On the other hand, less important frequencies do not have to be exact. A coarser coding scheme can be used, even though some of the finer (but less important) details will be lost in the coding.

## Instruction

Change **pop1_path** in code to apropriate for your setup.
Audio file should be in **.wav** format.
Start the program to see the outputs.
