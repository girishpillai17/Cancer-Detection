Problem :

Classify the given genetic variations(Gene & Variation) based on 
evidence from text-based clinical literature.

Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/

Data: Memorial Sloan Kettering Cancer Center (MSKCC) 

We have two data files: one conatins the information about the genetic 
mutations and the other contains the clinical evidence (text) that human 
experts/pathologists use to classify the genetic mutations.
Both these data files are have a common column called ID

Data file's information:

    training_variants (ID , Gene, Variations, Class)
    training_text (ID, Text)

Example Data point:

	Training Feature(Gene, Variation)

		ID,Gene,Variation,Class
		0,FAM58A,Truncating Mutations,1
		1,CBL,W802*,2
		2,CBL,Q249E,2

There are nine different classes a genetic mutation can be classified 
into => Multi class classification problem
