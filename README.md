### Creating a environment to the tensorflow

https://www.tensorflow.org/install/pip

* Install python
* Activate venv
* Install tensorflow only cpu

### Running IRIS app
```shell
python main_iris.py
```

### Running CIFAR-10 app
```shell
python main_cifar_10.py
```

## Legends
* accuracy: the percentage of predictions the model.
* loss: the loss function is a measure of how far the model's predictions are from the actual labels.
* val_accuracy: the validation accuracy is a measured on the validation dataset. 
* val_loss: the validation loss is the loss computed on the validation dataset after each epoch.

### Result after running both apps
```shell
python main_iris.py
Epoch 1/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 2s 34ms/step - accuracy: 0.5700 - loss: 1.0617 - val_accuracy: 0.5000 - val_loss: 1.0007
Epoch 2/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.6279 - loss: 0.9218 - val_accuracy: 0.7500 - val_loss: 0.9235
Epoch 3/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.7436 - loss: 0.7935 - val_accuracy: 0.7500 - val_loss: 0.8571
Epoch 4/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.8243 - loss: 0.6798 - val_accuracy: 0.7500 - val_loss: 0.7991
Epoch 5/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.8252 - loss: 0.6429 - val_accuracy: 0.8333 - val_loss: 0.7436
Epoch 6/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.8202 - loss: 0.5723 - val_accuracy: 0.8333 - val_loss: 0.6927
Epoch 7/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.8061 - loss: 0.5673 - val_accuracy: 0.8333 - val_loss: 0.6483
Epoch 8/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.8552 - loss: 0.5036 - val_accuracy: 0.9167 - val_loss: 0.6058
Epoch 9/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.8466 - loss: 0.4476 - val_accuracy: 0.9167 - val_loss: 0.5728
Epoch 10/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.8360 - loss: 0.4406 - val_accuracy: 0.9167 - val_loss: 0.5393
Epoch 11/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.8440 - loss: 0.4087 - val_accuracy: 0.9167 - val_loss: 0.5164
Epoch 12/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.8810 - loss: 0.3591 - val_accuracy: 0.9167 - val_loss: 0.4940
Epoch 13/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.8613 - loss: 0.3577 - val_accuracy: 0.9167 - val_loss: 0.4714
Epoch 14/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9013 - loss: 0.2945 - val_accuracy: 0.9167 - val_loss: 0.4530
Epoch 15/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9022 - loss: 0.2935 - val_accuracy: 0.9167 - val_loss: 0.4316
Epoch 16/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 11ms/step - accuracy: 0.9141 - loss: 0.2689 - val_accuracy: 0.9167 - val_loss: 0.4090
Epoch 17/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 10ms/step - accuracy: 0.9057 - loss: 0.2613 - val_accuracy: 0.9167 - val_loss: 0.3973
Epoch 18/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9375 - loss: 0.2413 - val_accuracy: 0.9167 - val_loss: 0.3903
Epoch 19/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9259 - loss: 0.2274 - val_accuracy: 0.9167 - val_loss: 0.3740
Epoch 20/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9083 - loss: 0.2296 - val_accuracy: 0.9167 - val_loss: 0.3507
Epoch 21/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 14ms/step - accuracy: 0.9601 - loss: 0.1883 - val_accuracy: 0.9167 - val_loss: 0.3401
Epoch 22/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 10ms/step - accuracy: 0.9626 - loss: 0.2072 - val_accuracy: 0.9167 - val_loss: 0.3285
Epoch 23/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 12ms/step - accuracy: 0.9331 - loss: 0.1939 - val_accuracy: 0.9167 - val_loss: 0.3169
Epoch 24/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 12ms/step - accuracy: 0.9441 - loss: 0.2105 - val_accuracy: 0.9167 - val_loss: 0.3144
Epoch 25/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9578 - loss: 0.1645 - val_accuracy: 0.9167 - val_loss: 0.3032
Epoch 26/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9736 - loss: 0.1361 - val_accuracy: 0.9167 - val_loss: 0.3003
Epoch 27/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9646 - loss: 0.1366 - val_accuracy: 0.9167 - val_loss: 0.2885
Epoch 28/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9643 - loss: 0.1340 - val_accuracy: 0.9167 - val_loss: 0.2829
Epoch 29/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9594 - loss: 0.1310 - val_accuracy: 0.9167 - val_loss: 0.2839
Epoch 30/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9687 - loss: 0.1160 - val_accuracy: 0.9167 - val_loss: 0.2920
Epoch 31/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9583 - loss: 0.1326 - val_accuracy: 0.9167 - val_loss: 0.3085
Epoch 32/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9695 - loss: 0.1157 - val_accuracy: 0.9167 - val_loss: 0.2961
Epoch 33/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 14ms/step - accuracy: 0.9780 - loss: 0.1119 - val_accuracy: 0.9167 - val_loss: 0.2908
Epoch 34/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9688 - loss: 0.1200 - val_accuracy: 0.9167 - val_loss: 0.3000
Epoch 35/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9912 - loss: 0.0832 - val_accuracy: 0.9167 - val_loss: 0.2904
Epoch 36/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9941 - loss: 0.0798 - val_accuracy: 0.9167 - val_loss: 0.3062
Epoch 37/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9906 - loss: 0.0783 - val_accuracy: 0.9167 - val_loss: 0.3199
Epoch 38/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9838 - loss: 0.0762 - val_accuracy: 0.9167 - val_loss: 0.3304
Epoch 39/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 10ms/step - accuracy: 0.9864 - loss: 0.1009 - val_accuracy: 0.9167 - val_loss: 0.3248
Epoch 40/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9892 - loss: 0.0711 - val_accuracy: 0.9167 - val_loss: 0.3175
Epoch 41/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9886 - loss: 0.0748 - val_accuracy: 0.9167 - val_loss: 0.3298
Epoch 42/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9705 - loss: 0.0881 - val_accuracy: 0.9167 - val_loss: 0.3499
Epoch 43/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9831 - loss: 0.0734 - val_accuracy: 0.9167 - val_loss: 0.3483
Epoch 44/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 6ms/step - accuracy: 0.9912 - loss: 0.0600 - val_accuracy: 0.9167 - val_loss: 0.3364
Epoch 45/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9759 - loss: 0.0822 - val_accuracy: 0.9167 - val_loss: 0.3247
Epoch 46/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9734 - loss: 0.0705 - val_accuracy: 0.9167 - val_loss: 0.3630
Epoch 47/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9977 - loss: 0.0520 - val_accuracy: 0.9167 - val_loss: 0.3561
Epoch 48/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9948 - loss: 0.0617 - val_accuracy: 0.9167 - val_loss: 0.3618
Epoch 49/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9920 - loss: 0.0628 - val_accuracy: 0.9167 - val_loss: 0.3658
Epoch 50/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9948 - loss: 0.0700 - val_accuracy: 0.9167 - val_loss: 0.3537
Epoch 51/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9857 - loss: 0.0630 - val_accuracy: 0.9167 - val_loss: 0.3631
Epoch 52/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9898 - loss: 0.0381 - val_accuracy: 0.9167 - val_loss: 0.3744
Epoch 53/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9953 - loss: 0.0457 - val_accuracy: 0.9167 - val_loss: 0.3771
Epoch 54/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9785 - loss: 0.0719 - val_accuracy: 0.9167 - val_loss: 0.4007
Epoch 55/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9949 - loss: 0.0580 - val_accuracy: 0.9167 - val_loss: 0.3866
Epoch 56/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9785 - loss: 0.0894 - val_accuracy: 0.9167 - val_loss: 0.3886
Epoch 57/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 6ms/step - accuracy: 0.9762 - loss: 0.0718 - val_accuracy: 0.9167 - val_loss: 0.3894
Epoch 58/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9902 - loss: 0.0586 - val_accuracy: 0.9167 - val_loss: 0.4087
Epoch 59/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9977 - loss: 0.0619 - val_accuracy: 0.9167 - val_loss: 0.3787
Epoch 60/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9983 - loss: 0.0541 - val_accuracy: 0.9167 - val_loss: 0.3775
Epoch 61/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9864 - loss: 0.0562 - val_accuracy: 0.9167 - val_loss: 0.4319
Epoch 62/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9977 - loss: 0.0583 - val_accuracy: 0.9167 - val_loss: 0.4162
Epoch 63/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9903 - loss: 0.0467 - val_accuracy: 0.9167 - val_loss: 0.4263
Epoch 64/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9977 - loss: 0.0332 - val_accuracy: 0.9167 - val_loss: 0.4223
Epoch 65/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9903 - loss: 0.0528 - val_accuracy: 0.9167 - val_loss: 0.4304
Epoch 66/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 10ms/step - accuracy: 0.9903 - loss: 0.0477 - val_accuracy: 0.9167 - val_loss: 0.4328
Epoch 67/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9864 - loss: 0.0406 - val_accuracy: 0.9167 - val_loss: 0.4250
Epoch 68/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9925 - loss: 0.0394 - val_accuracy: 0.9167 - val_loss: 0.4136
Epoch 69/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9866 - loss: 0.0410 - val_accuracy: 0.9167 - val_loss: 0.4297
Epoch 70/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9928 - loss: 0.0425 - val_accuracy: 0.9167 - val_loss: 0.4685
Epoch 71/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9981 - loss: 0.0485 - val_accuracy: 0.9167 - val_loss: 0.4214
Epoch 72/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9903 - loss: 0.0556 - val_accuracy: 0.9167 - val_loss: 0.4440
Epoch 73/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9974 - loss: 0.0376 - val_accuracy: 0.9167 - val_loss: 0.4492
Epoch 74/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9871 - loss: 0.0468 - val_accuracy: 0.9167 - val_loss: 0.4640
Epoch 75/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9964 - loss: 0.0320 - val_accuracy: 0.9167 - val_loss: 0.4472
Epoch 76/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9977 - loss: 0.0338 - val_accuracy: 0.9167 - val_loss: 0.4413
Epoch 77/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9948 - loss: 0.0378 - val_accuracy: 0.9167 - val_loss: 0.4637
Epoch 78/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9964 - loss: 0.0471 - val_accuracy: 0.9167 - val_loss: 0.4807
Epoch 79/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9785 - loss: 0.0564 - val_accuracy: 0.9167 - val_loss: 0.4821
Epoch 80/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9864 - loss: 0.0596 - val_accuracy: 0.9167 - val_loss: 0.4572
Epoch 81/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9929 - loss: 0.0438 - val_accuracy: 0.9167 - val_loss: 0.4515
Epoch 82/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9964 - loss: 0.0355 - val_accuracy: 0.9167 - val_loss: 0.4600
Epoch 83/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 10ms/step - accuracy: 0.9977 - loss: 0.0324 - val_accuracy: 0.9167 - val_loss: 0.4669
Epoch 84/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9936 - loss: 0.0411 - val_accuracy: 0.9167 - val_loss: 0.5067
Epoch 85/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9948 - loss: 0.0405 - val_accuracy: 0.9167 - val_loss: 0.4992
Epoch 86/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9871 - loss: 0.0521 - val_accuracy: 0.9167 - val_loss: 0.4919
Epoch 87/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 9ms/step - accuracy: 0.9868 - loss: 0.0456 - val_accuracy: 0.9167 - val_loss: 0.4944
Epoch 88/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 10ms/step - accuracy: 0.9948 - loss: 0.0329 - val_accuracy: 0.9167 - val_loss: 0.4930
Epoch 89/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 10ms/step - accuracy: 0.9948 - loss: 0.0354 - val_accuracy: 0.9167 - val_loss: 0.4647
Epoch 90/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9785 - loss: 0.0559 - val_accuracy: 0.9167 - val_loss: 0.4941
Epoch 91/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9977 - loss: 0.0298 - val_accuracy: 0.9167 - val_loss: 0.4636
Epoch 92/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9866 - loss: 0.0406 - val_accuracy: 0.9167 - val_loss: 0.5152
Epoch 93/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9812 - loss: 0.0395 - val_accuracy: 0.9167 - val_loss: 0.5026
Epoch 94/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 6ms/step - accuracy: 0.9948 - loss: 0.0325 - val_accuracy: 0.9167 - val_loss: 0.4860
Epoch 95/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 7ms/step - accuracy: 0.9948 - loss: 0.0322 - val_accuracy: 0.9167 - val_loss: 0.4756
Epoch 96/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 8ms/step - accuracy: 0.9929 - loss: 0.0366 - val_accuracy: 0.9167 - val_loss: 0.4882
Epoch 97/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 14ms/step - accuracy: 0.9864 - loss: 0.0460 - val_accuracy: 0.9167 - val_loss: 0.5219
Epoch 98/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 12ms/step - accuracy: 0.9903 - loss: 0.0359 - val_accuracy: 0.9167 - val_loss: 0.5172
Epoch 99/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 13ms/step - accuracy: 0.9864 - loss: 0.0396 - val_accuracy: 0.9167 - val_loss: 0.5024
Epoch 100/100
7/7 ━━━━━━━━━━━━━━━━━━━━ 0s 10ms/step - accuracy: 0.9785 - loss: 0.0472 - val_accuracy: 0.9167 - val_loss: 0.4872
1/1 - 0s - 22ms/step - accuracy: 1.0000 - loss: 0.0171
Test accuracy: 1.00
```

```shell
python main_cifar_10.py
Epoch 1/10
704/704 ━━━━━━━━━━━━━━━━━━━━ 183s 252ms/step - accuracy: 0.3263 - loss: 1.7939 - val_accuracy: 0.5950 - val_loss: 1.1345
Epoch 2/10
704/704 ━━━━━━━━━━━━━━━━━━━━ 174s 248ms/step - accuracy: 0.6068 - loss: 1.0804 - val_accuracy: 0.6756 - val_loss: 0.9282
Epoch 3/10
704/704 ━━━━━━━━━━━━━━━━━━━━ 189s 268ms/step - accuracy: 0.7085 - loss: 0.8196 - val_accuracy: 0.6968 - val_loss: 0.8758
Epoch 4/10
704/704 ━━━━━━━━━━━━━━━━━━━━ 168s 238ms/step - accuracy: 0.7668 - loss: 0.6590 - val_accuracy: 0.7464 - val_loss: 0.7342
Epoch 5/10
704/704 ━━━━━━━━━━━━━━━━━━━━ 248s 352ms/step - accuracy: 0.8060 - loss: 0.5510 - val_accuracy: 0.7420 - val_loss: 0.7744
Epoch 6/10
704/704 ━━━━━━━━━━━━━━━━━━━━ 264s 376ms/step - accuracy: 0.8408 - loss: 0.4461 - val_accuracy: 0.7646 - val_loss: 0.7001
Epoch 7/10
704/704 ━━━━━━━━━━━━━━━━━━━━ 187s 266ms/step - accuracy: 0.8759 - loss: 0.3473 - val_accuracy: 0.7740 - val_loss: 0.7097
Epoch 8/10
704/704 ━━━━━━━━━━━━━━━━━━━━ 194s 276ms/step - accuracy: 0.9051 - loss: 0.2707 - val_accuracy: 0.7850 - val_loss: 0.7652
Epoch 9/10
704/704 ━━━━━━━━━━━━━━━━━━━━ 195s 277ms/step - accuracy: 0.9278 - loss: 0.2063 - val_accuracy: 0.7576 - val_loss: 0.8895
Epoch 10/10
704/704 ━━━━━━━━━━━━━━━━━━━━ 198s 281ms/step - accuracy: 0.9340 - loss: 0.1845 - val_accuracy: 0.7744 - val_loss: 0.9845
313/313 - 11s - 36ms/step - accuracy: 0.7633 - loss: 1.0225
Test accuracy: 0.76
```