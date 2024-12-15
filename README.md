# Datasci 3 Capstone
Description of trials. Check .ipynb notebooks for more detailed information.

## Trials
1. epoch=10, batch=32, img=128x128, 1 conv, 128 dense, softmax, adam, Original dataset (-)
2. epoch=10, batch=32, img=128x128, 1 conv, 128 dense, softmax, adam, Revised dataset (+) 
3. epoch=10, batch=32, img=128x128, 3 conv, 128 dense, softmax, adam (+) 
4. epoch=10, batch=32, img=128x128, 3 conv, 128 dense, dropout, softmax, adam (+) 
5. epoch=10, batch=32, img=128x128, 3 conv, 128 dense, dropout, batch normalization, softmax, adam (?) 
6. epoch=20, batch=32, img=128x128, 3 conv, 128 dense, dropout, batch normalization, softmax, adam (+) 
7. epoch=20, batch=64, img=128x128, 3 conv, 128 dense, dropout, batch normalization, softmax, adam (+) 
8. epoch=20, batch=64, img=256x256, 3 conv, 128 dense, dropout, batch normalization, softmax, adam (+) 
9. epoch=20, batch=128, img=256x256, 3 conv, 128 dense, dropout, batch normalization, softmax, adam (-)  
10. epoch=20, batch=64, img=256x256, 3 conv, 128 dense, dropout, batch normalization, softmax, adam, aug (+)
11. epoch=40, batch=64, img=256x256, 3 conv, 128 dense, dropout, batch normalization, softmax, adam, aug (-)
12. epoch=20, batch=64, img=256x256, 3 conv, 256 dense, dropout, batch normalization, softmax, adam, aug (+)
13. epoch=20, batch=64, img=256x256, 3 conv, 512 dense, dropout, batch normalization, softmax, adam, aug (-)
14. epoch=20, batch=64, img=256x256, 3 conv, 256 dense, dropout, batch normalization, relu, adam, aug (-)
15. epoch=20, batch=64, img=256x256, 3 conv, 256 dense, dropout, batch normalization, sigmoid, adam, aug (-)
16. epoch=20, batch=64, img=256x256, 3 conv, 256 dense, dropout, batch normalization, softmax, rmsprop, aug, (-)
17. epoch=20, batch=64, img=256x256, 3 conv, 256 dense, dropout, batch normalization, softmax, adam, aug, contrast_aug, brightness_aug (+)
18. epoch=20, batch=64, img=256x256, 3 conv, 256 dense, dropout, batch normalization, softmax, adam, aug, contrast_aug (-)
19. epoch=20, batch=64, img=256x256, 4 conv, 256 dense, dropout, batch normalization, softmax, adam, aug (+)
20. epoch=20, batch=64, img=256x256, 5 conv, 256 dense, dropout, batch normalization, softmax, adam, aug (+)
