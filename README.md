# AI for Accessibility: Virtual Assistant for Hearing Impaired

Abstract - 

Speech is one of the essential communication methods for human beings. The present solutions available for people with hearing disabilities are limited due to accessibility and expensive due to the high cost of hardware components. Sound classification methods are primarily used in smart assistants and smart home products. This technology has a lot of potential and can be inculcated in an application-based solution for deaf people. Apart from this, solutions pertaining to Sign Language Recognition are limited in usability and features as most of these products are limited to only the alphabet's recognition, which is real-world usage is inadequate. With the advancement in pose estimation algorithms, a solution can be developed which can recognize words and sentences to improve the efficiency of daily communication.

We set out to create an impactful solution for anyone who can benefit from improved accessibility to everyday sound events. Our mobile application uses artificial intelligence to recognize key sound events of interest to the community such as emergency vehicle sirens and door knocks where immediate alerts and continuous logging is critical for the user. While there are many audio accessibility innovations in the app space, up until the time of writing it has been mostly in the areas of sound amplification and text to speech/speech to text. This app is optimized for Android with low-latency so that it works in real-time for the user.

The app converts a sound wave (from the mic) into a mel-spectrogram image that serves as the main feature fed into a Convolutional Neural Network that will then classify the sound into one of eight classes. Average inference time is about 15 ms so the user never has to worry about missing a beat and the app can also be synced with a wearable device.

#### UI Screenshots

| ![activated](https://github.com/stp8954/AwesomeAI/blob/master/image/image2.jpg)| ![prediction](https://github.com/stp8954/AwesomeAI/blob/master/image/image3.jpg)     |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | 
| ![settings](https://github.com/stp8954/AwesomeAI/blob/master/image/image4.jpg) | ![event selector](https://github.com/stp8954/AwesomeAI/blob/master/image/image5.jpg) |

## Pipeline Overview

![pipeline](https://github.com/stp8954/AwesomeAI/blob/master/image/pipeline.png)

## Performance Overview

- 110 MB Peak Memory Usage
- 5% Average, 10% Peak CPU Usage
- 10-15% Battery Life Penalty

Algorithmic performance:

![pipeline](https://github.com/stp8954/AwesomeAI/blob/master/image/performance.png)

## Suggested Contributions

1. Enable "wake word" detection based on user's name
2. Cross-platform support
3. Sensitivity (threshold tuning)
4. General accuracy improvements with minimal power usage penalty
