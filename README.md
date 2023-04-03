# svm-cs490

For the SVM model, do not drop the features "team", "Opponent", "Winner" and "W/L" when selecting features as they are needed for encoding later on. 

Any other features that are added that are strings need to be encoded. 

There's an issue with games that have "Type" as "NCAA" having NaNs in the features. SVM cannot work with NaN data so only a few games can be selected as NCAA tournament games. Need to figure something out. 
