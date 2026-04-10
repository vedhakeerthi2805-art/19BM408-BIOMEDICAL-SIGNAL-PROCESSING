# ECG Signal Analysis and QRS Detection using MATLAB
# AIM:

To analyze an ECG signal and detect QRS complexes using MATLAB.

# THEORY:

Electrocardiography (ECG) is a diagnostic technique used to measure the electrical activity of the heart. The ECG signal is generated due to the depolarization and repolarization of cardiac muscle cells during each heartbeat.
A typical ECG waveform consists of several components:

•	P wave – atrial depolarization

•	QRS complex – ventricular depolarization

•	T wave – ventricular repolarization

Among these components, the QRS complex has the highest amplitude and is the most significant feature used for detecting heart rate and cardiac abnormalities.
ECG signals are often affected by noise such as:

•	baseline wander

•	muscle noise

•	power-line interference (50 Hz)

Signal processing techniques are used to filter noise and extract useful features from ECG signals. One important technique is QRS detection, which identifies the location of ventricular depolarization peaks.
MATLAB provides functions such as findpeaks() that help detect QRS complexes automatically. Detecting QRS peaks allows biomedical engineers and doctors to calculate heart rate and identify arrhythmias.

# ALGORITHM :
1.	Load ECG signal data.
2.	Define the sampling frequency.
3.	Plot the ECG signal waveform.
4.	Apply a threshold-based method to detect QRS peaks.
5.	Mark the detected peaks on the ECG signal.
6.	Display the result.

# MATLAB CODE :
<img width="1080" height="761" alt="image" src="https://github.com/user-attachments/assets/5dae8b9f-e7cc-4dca-905b-83d841309564" />

# OUTPUT GRAPH :
![WhatsApp Image 2026-04-10 at 6 49 28 PM](https://github.com/user-attachments/assets/d3bfb2e7-5a5e-44ce-9f37-a2b216351117)



# RESULT :
The ECG signal was analyzed and QRS complexes were successfully detected using MATLAB.

