# Working with Audio in Python

This project is an introduction to using Python for interpreting audio data. The notebook covers several key concepts related to audio in digital form, including frequency, intensity, and sample rate.

The dataset can be downloaded here: **https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio**.

# Imports

The project starts with importing the necessary Python libraries, including `pandas`, `numpy`, `matplotlib`, `seaborn`, `glob`, `librosa`, and `IPython`.

# Terms to know for Audio in Digital Form

This section introduces the key terms related to audio in digital form, including frequency, intensity, and sample rate. The frequency describes the differences in wave lengths, and we interpret frequency as high and low pitches. Intensity describes the amplitude or height of the wave. Sample rate is specific to how the computer reads in the audio file and is often referred to as the "resolution" of the audio.

# Reading in Audio Files

The next section covers how to read in audio files using Python. The project uses the `glob` library to read in multiple types of audio files, including mp3, wav, m4a, flac, and ogg. The `librosa` library is used to load the audio data and retrieve information about the audio, such as the sample rate, shape, and raw audio data.

# Spectogram

This section covers how to create a spectrogram using Python. A spectrogram is a visual representation of the frequency content of a signal as it changes over time. The project uses the `librosa` library to calculate the Short-time Fourier Transform (STFT) of the audio data and convert it to a spectrogram using the `amplitude_to_db` function.

# Mel Spectogram

Finally, the project covers how to create a Mel spectrogram using Python. A Mel spectrogram is similar to a regular spectrogram but uses a Mel scale for the frequency axis. The project uses the librosa library to calculate the Mel spectrogram and convert it to a visual representation using the `amplitude_to_db` function.

Overall, this project provides an excellent starting point for anyone interested in working with audio in Python. The concepts and techniques covered in this notebook can be extended to a wide range of audio analysis tasks, from music analysis to speech recognition.
