# SonanciaDataSet
Raw sound files (.wav format) and their specific pairwise preferences for different affective dimensions.

# Sonancia Crowdsourcing DataSet

This DataSet includes the crowdsourcing annotations used to train audio affect models for the Sonancia system. If you end up using this dataset within your work, please cite the following paper: Lopes, Liapis and Yannakakis, "Modelling Affect for Horror Soundscapes", IEEE Transactions of Affective Computing, 2017.

#Preference Annotations

Preference annotations are organized in a .csv file where the name of each file refers what affect state was annotated. Affect states include: Arousal, Tension, Valence. 

Each line consists of a preference annotation such as: [Preferred_Sound_Name],[Unpreferred_Sound_Name]


# OpenSMILE Features

The features extracted with the OpenSMILE tool are also included from each sound file. Features were extracted following the "INTERSPEECH 2009 Emotional Challenge" by Schuller, Steidl and Batliner (2009).
