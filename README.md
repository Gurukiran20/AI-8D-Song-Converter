# AI-8D-Song-Converter
This project is an AI-powered 8D audio converter designed to transform ordinary audio files into an immersive 8D sound experience. By applying smooth circular panning effects and advanced reverb techniques, the converter creates the illusion of sound moving around the listener, enhancing the spatial audio experience

## Problem Statement
Standard audio files provide a flat, two-channel experience. This project aims to enhance the listening experience by adding an 8D effect, creating the illusion of sound moving around the listener’s head, making audio more immersive and engaging.

## Procedure
Audio Upload: The user uploads their audio file.
Audio Loading: The audio file is loaded using the librosa library.
8D Effect Application:
Stereo panning to create the illusion of sound movement.
Reverb effects using a convolution method for spatial depth.
Normalization ensures consistent audio levels.
Visualization: A waveform plot shows the difference between the left and right audio channels.
Export: The final 8D audio is exported as a .wav file and made available for download.

## Libraries Used

numpy — For numerical computations.
librosa — For audio analysis and manipulation.
soundfile — For reading and writing audio files.
scipy.signal — For applying convolution-based reverb.
matplotlib — For waveform visualization.
google.colab — For file uploads and downloads.

## How to Use
Open this project in Google Colab.
Upload your audio file when prompted.
The script will automatically convert your audio into an 8D version.
Visualize the left and right channel waveforms.
Download the newly created 8D audio file.

## Result
The converted audio file exhibits a distinct 8D effect. When listened to with headphones, the sound appears to move around the listener, providing an immersive auditory experience.
## Conclusion
This AI-powered 8D song converter successfully transforms standard audio files into immersive 8D audio experiences. With features like stereo panning, reverb, and normalization, it enhances the listening experience and opens opportunities for further audio manipulation and customization.
