# TRAC - 1
Repository hosting aggression-annotated dataset for the Shared Task on Aggression Identification during First Workshop on Trolling,  Aggression and Cyberbullying (TRAC - 1) at COLING - 2018. Please visit the workshop website - https://sites.google.com/view/trac1/home - for more details.

The repository contains two directories, which are self-explanatory. Both the directories contain 2 CSV files - agr_en_train.csv and agr_en_dev.csv in 'english' and agr_hi_train.csv and agr_hi_dev.csv in 'hindi'. 'agr_en_train.csv' and 'agr_hi_train.csv' contains the train set for the shared task in English and Hindi respectively. Similarly, 'dev' files contain data for developing and testing the model such that they do not overfit for the train set.

All the files contain 3 columns - first is the ID, second is a Facebook comment / post and the third is its aggression level. The columns are separated by comma and follows a minimal quoting pattern (such that only those columns are quoted which are in multiple lines or contain quotes in the text).
