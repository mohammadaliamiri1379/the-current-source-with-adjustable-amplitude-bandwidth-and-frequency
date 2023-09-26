# Design, implementation, and control of current source with adjustable amplitude, bandwidth, and frequency

## Project Overview:
This repository showcases the culmination of my final thesis work, which involved the design, implementation, and control of a current source with adjustable amplitude, bandwidth, and frequency. Dr. Farrokhi provided invaluable guidance and mentorship throughout the project. One of the significant challenges encountered during the project was the presence of process and measurement noise, which could potentially affect the accuracy of the output. To address this issue, we designed a suitable digital filter, specifically a FIR Kaiser filter, which effectively reduced the impact of noise and ensured reliable performance. By successfully integrating the designed current source, implementing control algorithms, and mitigating noise-related issues, this project demonstrated the effectiveness of our approach in achieving precise and adjustable current waveforms. This work not only provided a valuable opportunity for practical application of theoretical knowledge but also deepened my understanding of electronic systems, control theory, and digital signal processing.

## Key Features:
### User-Defined Curves: 
The primary goal of this project was to create a current (or voltage) source capable of closely following user-defined curves, providing flexibility for various applications.

### Arduino Due Microcontroller: 
We utilized an Arduino Due microcontroller with a programmed control system developed using MATLAB Simulink, ensuring precise control and high precision.

### Noise Mitigation: 
Addressing the challenge of process and measurement noise, we designed a custom digital filter, specifically a FIR Kaiser filter. This filter effectively reduces the impact of noise, ensuring the reliability and accuracy of the output.

### Effective Integration: 
Through the successful integration of the designed current source, control algorithms, and noise-mitigation techniques, this project exemplifies the effectiveness of our approach in achieving precise and adjustable current waveforms.
We've provided the MATLAB code for this project, allowing you to explore the details of our current source design and control system. You can find the code files in the [**MATLAB_Code**](/MATLAB_Code) directory.

## Simulink Models
In addition to the MATLAB code, we've included Simulink models for a visual representation of the chapter 3 and 4 and current_noise_ert_rtw.

## Real-Time Results
To get a glimpse of the real-time performance and visual representation of our current source, check out the finall pictures.
