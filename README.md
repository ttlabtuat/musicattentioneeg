

This is an EEG dataset of a selective attention task while listening to two musical excerpts simultaneously. Participants listened to two excerpts simultaneously but paying attention to one of the two. EEG data are 64-channel data from 14 subjects (seven males, seven females). Each subject performed a total of 68 trials. Each trial is about 60 s.



# Data Recording
EEG signals were measured using an EEG gel head cap (TMSi; Twente Medical Systems International, Oldenzaal, the Netherlands), with 64 scalp electrodes based on the international 10--10 system (Fp1, Fpz, Fp2, F7, F5, F1, F3, Fz, F2, F4, F6, F8, FC5, FC3, FC1, FCz, FC2, FC4, FC6, A1, T3, C5,C3, C1, Cz, C2, C4, C6, T4, A2, CP5, CP3, CP1, CPz, CP2, CP4, CP6, T5, T6, P5, P3, P1, Pz, P2, P4, P6, O1, Oz, O2, AF7, AF3, AF4, AF8, PO7, PO5, PO3, POz, PO4, PO6, PO8, FT7, FT8, TP7, and TP8).
As the patient ground, disposable electrodes were placed on the wrist.
Electroretinogram (EOG) signals were recorded simultaneously with the EEG signals.
EOG electrodes (microelectrode pair (bipolar), TMSi, the Netherlands) were at the corner of the right eye (referenced to the right earlobe) and above the right eye (referenced to the left earlobe).
All channels were amplified using a Refa 72-channel amplifier (TMSi, the Netherlands) against the average of all connected inputs.
The signals were sampled at a sampling rate of 2,048 Hz and recorded using Polybench (TMSi).
For synchronization of auditory stimuli with biological signals and behavioral experiment, audio signals and button signals were recorded by the Refa amplifier through a Dual Channel Isolation Amplifier (TMSi, the Netherlands).


# Participants
13 subjects (8 males, 5 females; mean age 21.73 years; range 20--23 years)
One of the participants was left-handed.
All participants had normal hearing.
They gave their written informed consent.
This study was approved by the Research Ethics Committee of Tokyo University of Agriculture and Technology.
どこかに参加者の性別，年齢，利き手をまとめたものを載せる


# Data Formats
- .csv->EEG signals

- .edf->EEG signals (edf)
We converted from csv to edf using pyEDFlib

# Column
- Time
- Events
- Fp1–PO8: EEG
- BIP65: EOG
- BIP66: EOG
- AUX69: audio
- AUX70: button (behavioral experiment)
- Digi: number of trial

# Note
- Day1: we played auditory stimulus on loudspeakers (705S2, B\&W, UK).
- Day2: we played auditory stimulus on earphone (ER-4S, Etymotic Research, USA).



