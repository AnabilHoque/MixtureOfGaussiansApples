# Implementation of Mixture of Gaussians to distinguish between Apple vs Non-Apple pixels.
- Part A: Load images in the apples folder, and defines some utility functions.
- Part B: We use mixtures of Gaussians to distinguish apple vs. non-apple pixels, using red, green, and blue as our dimensions.
- Part C: We show each pixel's posterior probability for being an "apple" for some test images found in the folder testApples.
- Part D: For the test image with a ground-truth mask, we quantify and report our result. This is done by applying a range of thresholds to the posterior to produce sets of {True Positives
 (TP), True Negatives (TN), False Positives (FP), and False Negatives (FN)} and using an ROC curve.
- Part E: We report qualitative and quantitative results for extra test images found in the testApples/myTests folder.
- Part D: We describe why we should be using three separate sets of files: a training set, a validation set, and a test set.