# Datasci 3 Capstone
Description of trials. Check .ipynb notebooks for more detailed information.

## Trials
1. Original dataset, epoch=10, batch=32, img=128x128, 1 convolutional layer
2. Updated dataset, epoch=10, batch=32, img=128x128, 1 convolutional layer
3. epoch=10, batch=32, img=128x128, 3 convolutional layers 
4. epoch=10, batch=32, img=128x128, added dropout layers
5. epoch=10, batch=32, img=128x128, added batch normalization
6. epoch=20, batch=32, img=128x128 
7. epoch=20, batch=64, img=128x128 (2nd best)
8. epoch=20, batch=64, img=256x256 (1st best)
9. epoch=20, batch=128, img=256x256 (dont use too many batches)
10. epoch=20, batch=128, img=128x128 (confirmed not to use too many batches)
11. epoch=20, batch=32, img=256x256
12. epoch=20, batch=32, img=256x256, shuffle val and test (got worse)
13. epoch=20, batch=64, img=256x256, shuffle val and test (got worse)
14. epoch=20, batch=64, img=256x256, augmented training data
