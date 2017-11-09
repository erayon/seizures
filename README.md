# seizures
Detection of Epileptic Seizure Event and Onset Using EEG using Machine Learning. As complete visual analysis of EEG signal is very difficult, automatic detection is preferred. Its a classification problem, first need to extract
features from the signal and add label onto them, based on that classification takes place.

# Introduction
Epilepsy is one of the most prevalent neurological disorders in human beings. It is characterized by
recurring seizures in which abnormal electrical activity in the brain causes the loss of consciousness or
a whole body convulsion. Patients are often unaware of the occurrence of seizure due to the random
nature of them which may increase the risk of physical injury. Studies show that 4-5% of the total
world population has been suffering from epilepsy.
Electroencephalogram is one of the important tools for diagnosis and analysis of epilepsy.
Electroencephalogram is the recorded representation of electrical activity produced by firing of neuron
within the brain along the scalp. For recording of EEG, electrodes will be pasted at some key points on
the patient's head. Electrodes pick up the signals and will be recorded in a recording device through
wires which are connected to electrodes. The “10-20” system is the internationally recognized method
to apply the location of electrodes in EEG recording. The “10-20” refers to the fact that actual distances
between electrodes are either 10% or 20% of front-back or right-left distance of the skull.


# Dataset Details
This database, collected at the Children’s Hospital Boston, consists of EEG recordings from pediatric
subjects with intractable seizures. Subjects were monitored for up to several days following withdrawal
of anti-seizure medication in order to characterize their seizures and assess their candidacy for surgical
intervention.

The sampling rate of the data was 173.61 Hz. The time series have the spectral bandwidth of the acquisition system, which is 0.5 Hz to 85 Hz. The dataset consists of five sets: Set B, Set C and Set E. 
1. Set B refers to healthy data
2. Set C refers to Inter-ictal (transition between healthy to seizure) data 
3. Set E is of ictal or seizures.

```
4097 data point per channel 
173.61 Hz sample rate and there are 4097 data point for each channel
total 100 channel are their
4097/173.61 = 23.59 sec 
the raw data from one of the channels for the 23.59 sec

```

![Alt text](fig1.png?raw=true "Visualization")


# Prerequisition
Python module with many functions for time series analysis, including brain physiological signals

```
1. Clone the repo via HTTPS:
$ git clone https://github.com/forrestbao/pyeeg.git
$ cd pyeeg
$ python setup.py install
$ python setup.py install --user

2. pip supports installing from a GitHub repo
Follow the [instructions for cloning](https://pip.pypa.io/en/latest/reference/pip_install.html#git)

```

# Feature Extraction 

# Problem Statement 
this is three classification proble
1. class1: healthy    ( 1 )
2. class2: transition ( 0 )
3. class3: seizures   (-1 )

