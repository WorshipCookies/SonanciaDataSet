# Sonancia Dataset

Sonancia is a system built for generating multiple facets of horror games, with the intention of creating tense and frightful experiences. Sonancia generates the architecture of a haunted mansion (with rooms and doors which may contain monsters or quest items) as well as the level's soundscape by allocating audio assets within the rooms and mixing them as the player traverses the level. Level generation and soundscape generation are orchestrated by notions of tension and suspense; the level generator attempts to match a designer-specified progression of tension while the sound generator attempts to prompt the player's suspense in rooms where tension is low.

If you just want to listen to each sound that is fine too! All sounds are easily accessible through Sonancia's own SoundCloud page (https://soundcloud.com/user-825231816).

# Sonancia Crowdsourcing DataSet

As part of the research for finding appropriate audio assets for use in Sonancia, a mapping between sound effects and perceived affect was derived based on crowdsourced preference annotations of a set of audio files. The audio files (in the folder Sounds), features (in the folder OpenSmile - Low Level Features), and crowdsourced preference annotations (in the folder Pairwise Preferences) are included in this project. If you use this dataset within your work, please cite the following paper: Lopes, Liapis and Yannakakis, "Modelling Affect for Horror Soundscapes", IEEE Transactions of Affective Computing, 2017.

# Preference Annotations

Preference annotations are organized in a .csv file where the name of each file refers what affect state was annotated. Affect states include: Arousal, Tension, Valence. 

Each line consists of a preference annotation such as: [Preferred_Sound_Name],[Unpreferred_Sound_Name]


# OpenSMILE Features

The features extracted with the OpenSMILE tool are also included from each sound file. Features were extracted following the "INTERSPEECH 2009 Emotional Challenge" by Schuller, Steidl and Batliner (2009).
