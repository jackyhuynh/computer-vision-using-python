# Introduction

## Images Structure
- Images are structure by R, G, B
- Work with number of RGB
- Goal of computer vision is to given computers human-level perception
- Computer vision is hard and fail most of the time

## Examles:
- OCR: take pictures from the licenses, if the user speeding will send the pics

# Images Filtering
- Point Operation: Change the value of 1 point (pixel)
- Neighborhood Operation: Change the value of 1 area (group of pixel)

## Dimensionality of an Image
- Each image have different dimensions

## The Gaussian Filter


## Mean Filter:
- Get the sum of each point and divide by the number

## Median Fiter:
- Either get black or white

## Sobel Filter:
- Sobel filter has gaussian inside it.
- There 2 two horizontal and vertical line

# Methods Sampling:
## Images down Sampling:
- How to lower resolution on an images without losing the information
- This is called the images pyramid

# Asline
- Take a sample of the realworld
- Sine-way is continuous

## Nyquist-Shannon Sampling Theory:
- Anti-aliasing in sampling:
  - Smooth the signal
  - Over-sample
- Low-pass filter: Allow low frequency to pass: smooth the images (a blur filter)
- High-pass filter:
  - Only keep the high frequencies
  - Edge detection (Sobel) is an example of high pass filter.
- Anti-aliasing
- Algorithm for down-sampling by factor of 2: Hybrid Images
- Gaussian image pyramid: sub-sampled images

## Understand Frequency as Wave
- The Fourier Series
- 