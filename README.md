# NeuralNetworkEEG-to-fMRI

![image](https://github.com/masal-98/NeuralNetworkEEG-to-fMRI/blob/16946d0ba08e7f4c90b99f0e1ac88309ccc80d34/img/cnn%20structure.PNG)

Simultaneous EEG-fMRI acquisitions are used to exploit the highly complementary characteristics of the two modalities, and this is of potential interest for neurofeedback (NF) applications aiming to modulate brain networks in the context of rehabilitation or therapeutic interventions. While EEG is not only inexpensive but also portable and easy to operate, fMRI is able to capture the activity of large brain areas or networks with much higher specificity. This complementarity has motivated the search for solutions capable of identifying EEG models that predict a given fMRI signal of interest, based on simultaneous EEG-fMRI recordings, so that appropriate EEG-based NF protocols can then be developed.

One important application is stroke neurorehabilitation strategies based on training brain motor circuits by performing motor imagery (MI) tasks, which can be reinforced by providing neurofeedback to the patient using EEG and/or fMRI. Previous work has been developed towards the estimation of fMRI-inspired EEG features targeting the activity of the amygdala or the motor cortex using linear regression techniques. Deep Learning techniques present great potential for the classification of EEG signals, but they have not yet been exploited for the purpose of predicting concurrent fMRI signals.

Here we aim to develop a Deep Learning strategy to estimate from EEG signals the fMRI activity in the motor cortex associated with a MI task. We used simultaneous EEG-fMRI data collected from healthy participants while performing MI tasks from a dataset collected at Instituto Superior Técnico de Lisboa. Since the Deep Learning approach to this task is novel, we have reviewed the literature in search of the most promising architecure.
The basis of this work is **EEGnet** a compact model which features explainability. Appropriate Deep Learning techniques and modifications to the model are considered and tested and their performance is evaluated.

![image](https://github.com/masal-98/NeuralNetworkEEG-to-fMRI/blob/6b0883d72790eaeebc553d0677a4ca2d8182f86f/img/in%20depth%20structure.PNG)
