# 🕵️ Predicting-Learning-Disabilities-ADHD-ASD-Dyslexia-via-Neural-Network
Predicting Learning Disabilities Detection Using Electroencephalogram Signals (EEG) is a prediction system that analyzes EEG signals from learning disabilities (LD) children.


# 🤝 Acknowledgements
I would like to express my sincere gratitude to Qhaisara (FYP Partner) & Dr. Zaliza (FYP Supervisor) for their invaluable contributions, guidance and support, which were instrumental in ensuring the success of the Final Year Project for the Bachelor's Degree.


# 📢 Disclaimer
The scripts were created specifically to run in Google Colab environment.


# 🧠🔍 Introduction
The system allows therapists to perform a quick assessment for early learning disabilities detection in children using the prediction system. Filtering the raw signal is done using BrainMarker software which applies a notch and bandpass filter to filter brainwave signals and allow EEG signals to be collected from 0.5 volts and up to 50 volts. Then, these raw signals is processed using Fast Fourier Transform to convert electrical signal to frequency data. Raw data that has been processed, are categorized into Alpha, Beta, Theta, Delta, and High-Beta frequency band waves and are assessed according to Ratio Test Approach. Upon classifying these bandwaves to respective 3 types of LD, the model can make prediction on the processed dataset via Multi Layer Perceptron Machine Learning. The system is mimicking techniques from robotic process automation (RPA) which is relatively new in the market where the therapist will have easy access to automatic learning disabilities detection.


# 🔌🛠️ Diagram of Electroencephalogram (EEG) Brain Node
<img width="718" height="762" alt="image" src="https://github.com/user-attachments/assets/8d09c269-058a-4ed5-a8e2-070886eada85" />


# 📈📊 Band-waves frequency of Brain Signals
<img width="717" height="293" alt="image" src="https://github.com/user-attachments/assets/85f39042-fce9-4acf-860d-49790dc0500d" />


# 🔗 Methodology
<img width="411" height="488" alt="image" src="https://github.com/user-attachments/assets/422cef91-efce-409c-808e-1141a1ea80cb" />


# 🌟 Result
<img width="550" height="682" alt="image" src="https://github.com/user-attachments/assets/7f13d5cb-db61-496c-a9c0-c7c4098b6c17" />


# 🚨 Remarks for Future Improvement
Future Enhancement to include more dataset to improve training curve of the model.


