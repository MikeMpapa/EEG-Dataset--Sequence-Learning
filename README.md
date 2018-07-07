# EEG-Dataset--Sequence-Learning


@article{Papakostas2017TowardsPT,
  title={Towards predicting task performance from EEG signals},
  author={Michalis Papakostas and Konstantinos Tsiakas and Theodoros Giannakopoulos and Fillia Makedon},
  journal={2017 IEEE International Conference on Big Data (Big Data)},
  year={2017},
  pages={4423-4425}
}


EEG Dataset for the paper: Towards Predicting Task Performance from EEG Signals 

--DATASET DESCRIPTION--
Dataset is devided into 10 folds for cross validation purposes

* File format: <SUBJECT_ID>_<SESSION_ID>_<ROUND_ID>

* Code available @ https://github.com/MikeMpapa/EEG-Sequence-Learning

* Npz file description (load with numpy)


    Each file includes all the signals captured with the MUSE for one round:

    1. RAW EEG

    2. A,B,D,G,T Frequency Abdolute Values

    3. A,B,D,G,T Frequency Relative Values

    4. A,B,D,G,T Frequency Scores --> Relative Value Compared to the most Recent Data distribution 

    5. C metric --> Concetration Value given by MUSE's digital component

    6. H metric --> Signal QUality metric



If you found our dataset usefull to your research please cite:

@article{Papakostas2017TowardsPT,
  title={Towards predicting task performance from EEG signals},
  author={Michalis Papakostas and Konstantinos Tsiakas and Theodoros Giannakopoulos and Fillia Makedon},
  journal={2017 IEEE International Conference on Big Data (Big Data)},
  year={2017},
  pages={4423-4425}
}
