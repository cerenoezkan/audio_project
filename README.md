# Audio Noise Reduction using Classical Signal Processing

A Digital Signal Processing (DSP) project that removes unwanted frequency components from noisy audio recordings using classical filtering techniques.

The project analyzes audio signals in the frequency domain, designs appropriate filters, and evaluates how effectively the filtered signal approaches the original clean recording.

> **Note:** This project intentionally avoids machine learning and AI-based denoising methods. Only traditional signal processing techniques are used.

---

## Project Overview

This project was developed as part of a university Digital Signal Processing course.

The objective is to:

- Analyze noisy audio recordings
- Identify unwanted frequency components
- Design suitable digital filters
- Remove noise from audio signals
- Compare the filtered output with the original clean signal
- Evaluate filtering performance both quantitatively and qualitatively

---

## Features

- Frequency-domain analysis using FFT/STFT
- Noise spectrum inspection
- Classical digital filter design
- Audio denoising
- Signal comparison before and after filtering
- Visualization of frequency spectra
- Objective and subjective performance evaluation

---

## Technologies

- Python
- NumPy
- SciPy
- Librosa
- Matplotlib

---

## Processing Pipeline

1. Load clean and noisy audio files
2. Transform signals into the frequency domain
3. Analyze dominant noise frequencies
4. Design appropriate filters
5. Apply filtering
6. Reconstruct the audio signal
7. Compare the filtered signal with the original clean recording
8. Visualize and evaluate the results

---

## Evaluation

The filtering performance is evaluated using:

- Frequency spectrum comparison
- Visual inspection of spectrograms
- Listening comparison
- Signal similarity analysis

---

## Project Structure

```
audio_project/
│
├── dataset/
│   ├── original/
│   └── noisy/
│
├── src/
│
├── results/
│
├── report/
│
└── README.md
```

---

## Dataset

The dataset consists of paired audio recordings:

- Original clean speech
- Corresponding noisy recordings

Each noisy sample is processed and compared with its clean counterpart.

---

## Limitations

This project intentionally excludes:

- Deep Learning
- Neural Networks
- Machine Learning-based denoising
- Pre-trained noise removal models

The objective is to demonstrate classical Digital Signal Processing techniques.

---

## Future Improvements

Possible extensions include:

- Adaptive filtering
- Wiener filtering
- Spectral subtraction
- Real-time audio denoising
- Performance optimization

---
