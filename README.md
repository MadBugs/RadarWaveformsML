# RadarWaveformsML
Manipulation of Radar and Communication Waveforms using new ML algorithms but not forgetting the Old Tricks

This repository was originally created for project for the Class "Introduction to Machine Learning at NYU Tandon" ministered by Professor Sundeep Ragan (more details at https://github.com/sdrangan/introml)

The main goal is to use synthetic radar waveforms provided by the scientists at the US National Institute of Standards and Technology (NIST) (more details at https://data.nist.gov/od/id/mds2-2116) to investigate the detection of features in the waveforms using *Machine Learning* techniques.

We are interested in simple trainable algorithms that able to detect the waveforms in the presence of noise (and also fading in the future). We are also interested in find the *signatures* of the waveforms to be able to classify the different radar waveforms and differentiate them from other electromagnetic signals, like the ones used for microwave wireless communications. 

Real-time time identification of waveforms is an important tool that can be used to allow coexistence of different emitters sharing the same geographical space. It is also relevant for cyber-security, helping to assure security in cyber-physical environments.

NOTE: to develop the code here we used examples provided in the NIST directory about how read the data files and label files fields correctly in the Python Programming Language. The MATLAB code used by the scientists at NIST to generated radar wavforms simililar to the ones they made availble can be found at https://github.com/usnistgov/SimulatedRadarWaveformGenerator.git/trunk

