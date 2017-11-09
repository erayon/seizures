# seizures
Detection of Epileptic Seizure Event and Onset Using EEG 

# Dataset Details
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


