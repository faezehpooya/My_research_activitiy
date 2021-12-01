# My_research_activitiy
# Protein Secondary Structure Prediction (PSSP)
## Summary:  
Padding approach:  
- all sequences are padded untill have the same length  
- 20 amino acid and their 3 secondary structures (E, H and t) or 8 secondary structures are used  

Sliding window approach:  
- sliding window with size 15 is used  
- secondary structure of middle amino acid is used for target structure  

## Features:
- Protovec  
- 9 physiochemical properties of Amino Acid form AAindex  
- one hot encoding representation of 9 physiochemical properties  
- one hot encoding  
- 4 properties including: Amino acids order, Hydropathy index, Polarity, and sequence length  

## Data:
Casp10,Casp 11, Casp12, Casp13, CB513, CB613

## Networks:

## ![model_3](https://user-images.githubusercontent.com/24568067/144295056-1bde0b04-2c23-4d38-a653-cc720718a72d.png)  
## ![model_4](https://user-images.githubusercontent.com/24568067/144295279-b27cab8c-8671-41ea-ae3a-16d58a566742.png)  
## ![build_model_a](https://user-images.githubusercontent.com/24568067/144295448-d2c21290-36b1-42bb-8279-d0e43d227f5e.png)  
## ![build_model_d](https://user-images.githubusercontent.com/24568067/144295466-9c400160-341f-4dd3-acfb-91d51b3165fa.png)  
## ![deep_aclstm_one_input](https://user-images.githubusercontent.com/24568067/144295480-e6c66771-f67a-4211-ba7a-02e11c29793a.png)

## Dependencies:  
- Tensorflow 2.5.0  
- Pandas  
- Numpy 1.19.5  
- Keras 2.5.0  




