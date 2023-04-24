# Tiny_ImageNet
### Multiclass classification of a subset of the Image_Net dataset : :

Code in comments will blur out the background of the training samples using the 
Bounded box information provided in every folder, the idea behind this being that
The model should pick up patterns only from the region of interest and not the background

Doing this results in faster decrease in training loss, but the difference in validation loss 
and training loss is high, as compared to use of normal images.

Just run the notebook!
