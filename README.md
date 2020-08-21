# EVA5-Phase1-Session5


1) EVA5Session5_1.ipynb

   The basic structure was set
   
   Made sure the code is working
   
   parameters = 6.3M
   
   max train accuracy: 99.90(12th and 15th epoch)
   
   max test accuracy: 99.24(13th epoch)
   
   The model is heavy and overfitting
   
   
2) EVA5Session5_code2.ipynb

   Set the basic skeleton correct
   
   Kept maxpooling in correct position
   
   Added GAP
   
   Increased the capacity by adding a layer after GAP
   
   Made total number of parameters less than 10k
   
   parameters = 9.4k
   
   max train accuracy: 98.53(15th epoch)
   
   max test accuracy: 98.35(13th epoch)
   
   Good model
   
   The model needs to be pushed further to hit 94% accuracy
   
3) EVA5Session5_code3.ipynb

   Added Batch normalization
   
   Added dropout(tried with different values, but attained target with value 0.02)
   
   parameters = 9.6k
   
   max train accuracy: 99.37(15th epoch)
   
   max test accuracy: 99.48(11th epoch)
   
   Good model
   
   Needs to be pushed further to get accuracy above 94% continuously
   
4) EVA5Session5_code4.ipynb 

   Added data augmentation - Rotation and Color Jitter
   
   parameters = 9.6k
   
   max train accuracy: 99.19(14th epoch)
   
   max test accuracy: 99.45(14th and 15th epoch)
   
   Good model 
   
   Reached test accuracy continuously above 99.4% from 12th epoch onwards.
   
   Less than 10k parameters
   
   
