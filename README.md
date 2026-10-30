# Plant Leaf Disease Classifier (Midterm)

A CNN that classifies tomato leaf diseases from photos.

## Dataset
PlantVillage (Kaggle), 5 tomato classes: healthy, early blight, late blight, leaf mold, septoria leaf spot.
Split: 70% train / 15% validation / 15% test.

## Model
Small CNN (3 convolution blocks), trained for 10 epochs on 128x128 images.

## Results
- Test accuracy: 89%
- Overfitting observed (train ~98% vs validation ~91%)
- Weakest classes: early blight and septoria leaf spot

## Limitations (planned for finals)
- Only lab photos, no real field images
- Only 5 of 15 classes
- No data augmentation
- Small images lose subtle spots
- No pretrained model
