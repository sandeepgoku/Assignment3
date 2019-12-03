Accuracy on test data is: 75.24
Model definition:
model_sep.add(SeparableConv2D(48, 3, strides=(1, 1), padding='valid', data_format=None, 
                             dilation_rate=(1, 1), depth_multiplier=1, activation=None, use_bias=True, 
                             depthwise_initializer='glorot_uniform', pointwise_initializer='glorot_uniform', 
                             bias_initializer='zeros', depthwise_regularizer=None, pointwise_regularizer=None, bias_regularizer=None, 
                             activity_regularizer=None, depthwise_constraint=None, pointwise_constraint=None, bias_constraint=None,input_shape=(32, 32, 3))) #output shape(30,30,48)
                             
50 Epochs values:                             
Epoch 1/50
390/390 [==============================] - 16s 41ms/step - loss: 2.1010 - acc: 0.1965 - val_loss: 1.8581 - val_acc: 0.3084
Epoch 2/50
390/390 [==============================] - 14s 35ms/step - loss: 1.7032 - acc: 0.3647 - val_loss: 1.5512 - val_acc: 0.4231
Epoch 3/50
390/390 [==============================] - 14s 35ms/step - loss: 1.5115 - acc: 0.4404 - val_loss: 1.4254 - val_acc: 0.4800
Epoch 4/50
390/390 [==============================] - 14s 35ms/step - loss: 1.4061 - acc: 0.4834 - val_loss: 1.2938 - val_acc: 0.5272
Epoch 5/50
390/390 [==============================] - 14s 35ms/step - loss: 1.3220 - acc: 0.5167 - val_loss: 1.2355 - val_acc: 0.5500
Epoch 6/50
390/390 [==============================] - 14s 35ms/step - loss: 1.2556 - acc: 0.5448 - val_loss: 1.2099 - val_acc: 0.5646
Epoch 7/50
390/390 [==============================] - 14s 35ms/step - loss: 1.2095 - acc: 0.5641 - val_loss: 1.1438 - val_acc: 0.5874
Epoch 8/50
390/390 [==============================] - 14s 35ms/step - loss: 1.1584 - acc: 0.5847 - val_loss: 1.1092 - val_acc: 0.5998
Epoch 9/50
390/390 [==============================] - 14s 35ms/step - loss: 1.1212 - acc: 0.5994 - val_loss: 1.0763 - val_acc: 0.6210
Epoch 10/50
390/390 [==============================] - 14s 35ms/step - loss: 1.0826 - acc: 0.6128 - val_loss: 1.0465 - val_acc: 0.6249
Epoch 11/50
390/390 [==============================] - 14s 35ms/step - loss: 1.0447 - acc: 0.6288 - val_loss: 0.9906 - val_acc: 0.6509
Epoch 12/50
390/390 [==============================] - 14s 35ms/step - loss: 1.0106 - acc: 0.6411 - val_loss: 0.9583 - val_acc: 0.6575
Epoch 13/50
390/390 [==============================] - 14s 35ms/step - loss: 0.9831 - acc: 0.6513 - val_loss: 0.9488 - val_acc: 0.6650
Epoch 14/50
390/390 [==============================] - 14s 35ms/step - loss: 0.9552 - acc: 0.6604 - val_loss: 0.9345 - val_acc: 0.6694
Epoch 15/50
390/390 [==============================] - 14s 35ms/step - loss: 0.9293 - acc: 0.6729 - val_loss: 0.8897 - val_acc: 0.6827
Epoch 16/50
390/390 [==============================] - 14s 35ms/step - loss: 0.9057 - acc: 0.6814 - val_loss: 0.8925 - val_acc: 0.6828
Epoch 17/50
390/390 [==============================] - 14s 35ms/step - loss: 0.8863 - acc: 0.6864 - val_loss: 0.8546 - val_acc: 0.6991
Epoch 18/50
390/390 [==============================] - 14s 35ms/step - loss: 0.8713 - acc: 0.6927 - val_loss: 0.8617 - val_acc: 0.6965
Epoch 19/50
390/390 [==============================] - 14s 35ms/step - loss: 0.8450 - acc: 0.7022 - val_loss: 0.8366 - val_acc: 0.7051
Epoch 20/50
390/390 [==============================] - 14s 35ms/step - loss: 0.8286 - acc: 0.7063 - val_loss: 0.8309 - val_acc: 0.7100
Epoch 21/50
390/390 [==============================] - 14s 35ms/step - loss: 0.8166 - acc: 0.7120 - val_loss: 0.8238 - val_acc: 0.7108
Epoch 22/50
390/390 [==============================] - 14s 35ms/step - loss: 0.8012 - acc: 0.7165 - val_loss: 0.8124 - val_acc: 0.7143
Epoch 23/50
390/390 [==============================] - 14s 35ms/step - loss: 0.7828 - acc: 0.7234 - val_loss: 0.7985 - val_acc: 0.7140
Epoch 24/50
390/390 [==============================] - 14s 35ms/step - loss: 0.7735 - acc: 0.7283 - val_loss: 0.7856 - val_acc: 0.7237
Epoch 25/50
390/390 [==============================] - 14s 35ms/step - loss: 0.7633 - acc: 0.7313 - val_loss: 0.7778 - val_acc: 0.7293
Epoch 26/50
390/390 [==============================] - 14s 35ms/step - loss: 0.7464 - acc: 0.7348 - val_loss: 0.8222 - val_acc: 0.7152
Epoch 27/50
390/390 [==============================] - 14s 35ms/step - loss: 0.7378 - acc: 0.7384 - val_loss: 0.7772 - val_acc: 0.7287
Epoch 28/50
390/390 [==============================] - 14s 35ms/step - loss: 0.7331 - acc: 0.7400 - val_loss: 0.7810 - val_acc: 0.7257
Epoch 29/50
390/390 [==============================] - 14s 35ms/step - loss: 0.7173 - acc: 0.7470 - val_loss: 0.7577 - val_acc: 0.7353
Epoch 30/50
390/390 [==============================] - 14s 35ms/step - loss: 0.7092 - acc: 0.7485 - val_loss: 0.7787 - val_acc: 0.7317
Epoch 31/50
390/390 [==============================] - 14s 35ms/step - loss: 0.7026 - acc: 0.7494 - val_loss: 0.7591 - val_acc: 0.7383
Epoch 32/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6908 - acc: 0.7554 - val_loss: 0.7369 - val_acc: 0.7428
Epoch 33/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6831 - acc: 0.7583 - val_loss: 0.7318 - val_acc: 0.7431
Epoch 34/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6742 - acc: 0.7614 - val_loss: 0.7334 - val_acc: 0.7444
Epoch 35/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6677 - acc: 0.7617 - val_loss: 0.7430 - val_acc: 0.7408
Epoch 36/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6638 - acc: 0.7627 - val_loss: 0.7365 - val_acc: 0.7483
Epoch 37/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6546 - acc: 0.7659 - val_loss: 0.7191 - val_acc: 0.7498
Epoch 38/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6434 - acc: 0.7711 - val_loss: 0.7435 - val_acc: 0.7413
Epoch 39/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6467 - acc: 0.7690 - val_loss: 0.7148 - val_acc: 0.7521
Epoch 40/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6314 - acc: 0.7743 - val_loss: 0.7213 - val_acc: 0.7494
Epoch 41/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6368 - acc: 0.7727 - val_loss: 0.7174 - val_acc: 0.7536
Epoch 42/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6264 - acc: 0.7743 - val_loss: 0.7362 - val_acc: 0.7494
Epoch 43/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6256 - acc: 0.7749 - val_loss: 0.7179 - val_acc: 0.7508
Epoch 44/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6123 - acc: 0.7825 - val_loss: 0.7199 - val_acc: 0.7514
Epoch 45/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6121 - acc: 0.7826 - val_loss: 0.7052 - val_acc: 0.7582
Epoch 46/50
390/390 [==============================] - 14s 35ms/step - loss: 0.6037 - acc: 0.7862 - val_loss: 0.7406 - val_acc: 0.7493
Epoch 47/50
390/390 [==============================] - 14s 35ms/step - loss: 0.5985 - acc: 0.7857 - val_loss: 0.7202 - val_acc: 0.7544
Epoch 48/50
390/390 [==============================] - 14s 35ms/step - loss: 0.5992 - acc: 0.7863 - val_loss: 0.7310 - val_acc: 0.7504
Epoch 49/50
390/390 [==============================] - 14s 35ms/step - loss: 0.5855 - acc: 0.7921 - val_loss: 0.7102 - val_acc: 0.7525
Epoch 50/50
390/390 [==============================] - 14s 35ms/step - loss: 0.5856 - acc: 0.7902 - val_loss: 0.7142 - val_acc: 0.7524
Model took 688.71 seconds to train
