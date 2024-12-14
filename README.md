# Datasci 3 Capstone
Description of trials. Check .ipynb notebooks for more detailed information.

## Trials
1. epoch=10, batch=32, img=128x128, 1 convolutional layer, 128 dense layer, Original dataset (class imbalance)
2. epoch=10, batch=32, img=128x128, 1 convolutional layer, 128 dense layer, Revised dataset (combine related classes to fix class imbalance)
3. epoch=10, batch=32, img=128x128, 3 convolutional layers, 128 dense layer
4. epoch=10, batch=32, img=128x128, 3 convolutional layers, , 128 dense layer, dropout layers
5. epoch=10, batch=32, img=128x128, 3 convolutional layers, , 128 dense layer, dropout layers, batch normalization
6. epoch=20, batch=32, img=128x128, 3 convolutional layers, , 128 dense layer, dropout layers, batch normalization
7. epoch=20, batch=64, img=128x128, 3 convolutional layers, , 128 dense layer, dropout layers, batch normalization
8. epoch=20, batch=64, img=256x256, 3 convolutional layers, , 128 dense layer, dropout layers, batch normalization
9. epoch=20, batch=128, img=256x256, 3 convolutional layers, , 128 dense layer, dropout layers, batch normalization (dont use too many batches)
10. epoch=20, batch=128, img=128x128, 3 convolutional layers, , 128 dense layer, dropout layers, batch normalization (confirmed not to use too many batches)
11. epoch=20, batch=32, img=128x128, 3 convolutional layers, , 128 dense layer, dropout layers, batch normalization (confirmed not to use too many batches)
12. epoch=20, batch=32, img=128x128, 3 convolutional layers, , 128 dense layer, dropout layers, batch normalization (shuffled val and test generators and got worse)
13. epoch=20, batch=64, img=128x128, 3 convolutional layers, , 128 dense layer, dropout layers, batch normalization (shuffled val and test generators and got worse)
14. epoch=20, batch=32, img=128x128, 3 convolutional layers, , 128 dense layer, dropout layers, batch normalization (augmented train generator)
15. epoch=40, batch=32, img=128x128, 3 convolutional layers, , 128 dense layer, dropout layers, batch normalization (too many epochs bad??)
16. epoch=40, batch=32, img=128x128, 3 convolutional layers, , 256 dense layer, dropout layers, batch normalization
