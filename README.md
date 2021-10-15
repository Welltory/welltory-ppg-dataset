# Welltory-PPG-dataset

Dataset consists of 21 records containing PPG with simultaneously collected RR intervals. PPG data was obtained via a smartphone camera using Welltory app.  Signal lengths vary from 68 to 112 seconds.

## Data collection protocol
Each participant attached index finger to a smartphone camera recording video. Each frame capture time (measured in milliseconds elapsed from the measurement start time) as well as the average values of red, green and blue channel in the frame were recorded. At the same time each participant was wearing the Polar H10 chest strap. After the end of the measurement the RR-intervals detected by the Polar device during the measurement were collected. Each dataset record consists of the following arrays:

- camera frame capture times in milliseconds
- values of the red, green, and blue channel in the camera frames
- sequence of RR intervals (in milliseconds) collected from the Polar device during the measurement

## Participants
Data was collected from 13 healthy volunteers of age 25-35. Each participant made 1 or 2 measurements using their own Android smartphone.

## Data description
There are 21 recordings stored in folders "subject_01", .., "subject_21"
Each folder "subject_.." contains:

- PPG.csv: 3 channel PPG signal containing camera frame capture time and values of red, green and blue channels in the frame.

- RR.txt: a text file containing RR intervals obtained by Polar device during the PPG measurements.

Please refer to datatypes.md for data format description

## Citation and copyright
This dataset can be used freely for research purposes. If you use this dataset in your research, please cite this publication:

> Neshitov, A.; Tyapochkin, K.; Smorodnikova, E.; Pravdin, P. Wavelet Analysis and Self-Similarity of Photoplethysmography Signals for HRV Estimation and Quality Assessment. Sensors 2021, 21, 6798. https://doi.org/10.3390/s21206798

## Contact
Konstantin Tyapochkin, konstantin (at) welltory.com
