---
title: Dataset
background: /assets/theme/images/bckg.png
permalink: /dataset/
---

### **<span style="color:#2B547E">SeizeIT2 Dataset – Validation and test set</span>**
\
![seizeit2]({{ '/assets/theme/images/sz2_setup.png' | relative_url }}){: .rounded .float-end}
The SeizeIT2 dataset is an international multicenter dataset (containing EEG and ECG) with more than 350 patients suffering from epilepsy and recorded both in home and hospital environments (the first ever phase-4 clinical trial for a wearable for in home monitoring for seizure detection). The data are acquired with the SD device and the current study is part of a larger multicenter trial with focus on clinical validation of the SD in people with typical absence, focal impaired awareness, and generalized tonic–clonic seizures. SeizeIT2 unites public and private stakeholders to address an unmet patient need. This is a continuation of [SeizeIT1](https://rdr.kuleuven.be/dataset.xhtml?persistentId=doi:10.48804/P5Q0OJ) ICON project, led by UCB, with partners from Un. de Navarra, Karolinska Institutet, KU Leuven, RWTH Aachen, Universitäts klinikum Aachen, Centro Hospitalar e Universitário de Coimbra, Oxford University Hospitals NHS Foundation Trust and Stockholms Läns Landsting. 
Patients underwent video-EEG monitoring using the standardized 25-electrode array of the International Federation of Clinical Neurophysiology. Behind each ear, two additional Ag/AgCl cup electrodes were attached on the mastoid bone for concomitant recording with the SD (the same electrode positions as the behind-the-ear EEG in SeizeIT1). The closest corresponding electrodes on 25-channel EEG were T7 and T8 for the top electrode and P9 and P10 for the lower electrode. The SD was attached on the upper back using a patch, and two bipolar channels were created by connecting the ipsilateral top and lower electrode. Impedance was ≤5 kΩ at the beginning and checked throughout. An additional SD sensor was placed on the left chest of patients with two electrodes measuring Electrocardiography data (ECG) and two electrodes on the left deltoid muscle measuring Electromypgraphy (EMG) data.

In the context of this challenge, only focal patients were included in the dataset. The data was subsequently separated in a fixed training, validation and test sets. The training and validation sets will be provided to participants, the test set is privately kept and used for the final evaluation.


#### Data format:

The raw data is in the form of **.edf** (European Data Format). The annotations are provided in **.tsv** (tab separated values) files. For every seizure, the first column represents the starting point (in seconds) and the second one the end point of the event. The third, fourth and fifth columns indicate the type of event and, if aplicable, the seizure hemisphere and lobe respectively. The last column contains extra information indicated by the annotators.
