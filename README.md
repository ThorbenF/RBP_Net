# RBP_Net

Supplementaries for 'RBP Grand Challenge - Generative ANN for RBP-binding site predictions'

Directory contains: 
- All scripts needed to produce results published in this study
- Produced results are and will be saved within the 'RBPNet_saves' directory

Generative_RBP_Net.ipynb justifies the use of a non-linear machine learning algorithm to be used based on a simplified model.
Generative_RBP_Net_NextNearestNeighbor_GenSeq.ipynb is the model using nearest neighbor sequence information up to nn=3. 
The model is trained on all available data and is expected to give reproducable results.
The model produces Generated_RBP_preferences3.txt and All_combinations_central_A3.txt, which can be compared at http://www.twosamplelogo.org
The trained model can be used immediately by executing all cells except ln[20], ln[21], ln[21], ln [28] and ln[31], because then the stored parameters of the ANN are used instead.