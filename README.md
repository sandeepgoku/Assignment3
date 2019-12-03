Accuracy on test data is: 78.47

Model definition:
model_sep.add(SeparableConv2D(48, 3, strides=(1, 1), padding='valid', data_format=None, 
                             dilation_rate=(1, 1), depth_multiplier=1, activation=None, use_bias=True, 
                             depthwise_initializer='glorot_uniform', pointwise_initializer='glorot_uniform', 
                             bias_initializer='zeros', depthwise_regularizer=None, pointwise_regularizer=None, bias_regularizer=None, 
                             activity_regularizer=None, depthwise_constraint=None, pointwise_constraint=None, bias_constraint=None,input_shape=(32, 32, 3)))
                             
Epoch 1/50
390/390 [==============================] - 20s 52ms/step - loss: 1.6179 - acc: 0.4120 - val_loss: 1.4122 - val_acc: 0.5001
Epoch 2/50
390/390 [==============================] - 14s 37ms/step - loss: 1.2472 - acc: 0.5567 - val_loss: 1.1621 - val_acc: 0.5911
Epoch 3/50
390/390 [==============================] - 14s 36ms/step - loss: 1.1014 - acc: 0.6067 - val_loss: 1.0630 - val_acc: 0.6234
Epoch 4/50
390/390 [==============================] - 14s 36ms/step - loss: 1.0056 - acc: 0.6417 - val_loss: 0.9812 - val_acc: 0.6596
Epoch 5/50
390/390 [==============================] - 14s 37ms/step - loss: 0.9336 - acc: 0.6697 - val_loss: 0.9450 - val_acc: 0.6700
Epoch 6/50
390/390 [==============================] - 14s 37ms/step - loss: 0.8832 - acc: 0.6887 - val_loss: 0.9033 - val_acc: 0.6833
Epoch 7/50
390/390 [==============================] - 14s 37ms/step - loss: 0.8368 - acc: 0.7049 - val_loss: 0.8531 - val_acc: 0.7079
Epoch 8/50
390/390 [==============================] - 14s 37ms/step - loss: 0.8000 - acc: 0.7158 - val_loss: 0.8300 - val_acc: 0.7139
Epoch 9/50
390/390 [==============================] - 14s 36ms/step - loss: 0.7688 - acc: 0.7290 - val_loss: 0.7899 - val_acc: 0.7254
Epoch 10/50
390/390 [==============================] - 14s 37ms/step - loss: 0.7350 - acc: 0.7403 - val_loss: 0.8131 - val_acc: 0.7191
Epoch 11/50
390/390 [==============================] - 14s 37ms/step - loss: 0.7191 - acc: 0.7461 - val_loss: 0.7837 - val_acc: 0.7320
Epoch 12/50
390/390 [==============================] - 14s 37ms/step - loss: 0.6963 - acc: 0.7571 - val_loss: 0.7655 - val_acc: 0.7377
Epoch 13/50
390/390 [==============================] - 14s 37ms/step - loss: 0.6778 - acc: 0.7610 - val_loss: 0.8097 - val_acc: 0.7201
Epoch 14/50
390/390 [==============================] - 14s 37ms/step - loss: 0.6577 - acc: 0.7664 - val_loss: 0.7576 - val_acc: 0.7397
Epoch 15/50
390/390 [==============================] - 14s 37ms/step - loss: 0.6441 - acc: 0.7719 - val_loss: 0.7717 - val_acc: 0.7373
Epoch 16/50
390/390 [==============================] - 14s 37ms/step - loss: 0.6225 - acc: 0.7774 - val_loss: 0.7502 - val_acc: 0.7446
Epoch 17/50
390/390 [==============================] - 14s 37ms/step - loss: 0.6128 - acc: 0.7814 - val_loss: 0.7358 - val_acc: 0.7516
Epoch 18/50
390/390 [==============================] - 14s 37ms/step - loss: 0.6022 - acc: 0.7866 - val_loss: 0.7335 - val_acc: 0.7525
Epoch 19/50
390/390 [==============================] - 14s 37ms/step - loss: 0.5873 - acc: 0.7917 - val_loss: 0.7054 - val_acc: 0.7626
Epoch 20/50
390/390 [==============================] - 14s 37ms/step - loss: 0.5777 - acc: 0.7950 - val_loss: 0.7234 - val_acc: 0.7566
Epoch 21/50
390/390 [==============================] - 14s 37ms/step - loss: 0.5673 - acc: 0.7989 - val_loss: 0.7139 - val_acc: 0.7588
Epoch 22/50
390/390 [==============================] - 14s 37ms/step - loss: 0.5594 - acc: 0.8009 - val_loss: 0.6797 - val_acc: 0.7682
Epoch 23/50
390/390 [==============================] - 14s 37ms/step - loss: 0.5502 - acc: 0.8047 - val_loss: 0.7298 - val_acc: 0.7566
Epoch 24/50
390/390 [==============================] - 14s 37ms/step - loss: 0.5456 - acc: 0.8046 - val_loss: 0.6881 - val_acc: 0.7680
Epoch 25/50
390/390 [==============================] - 14s 37ms/step - loss: 0.5316 - acc: 0.8113 - val_loss: 0.6990 - val_acc: 0.7674
Epoch 26/50
390/390 [==============================] - 15s 38ms/step - loss: 0.5295 - acc: 0.8109 - val_loss: 0.6817 - val_acc: 0.7691
Epoch 27/50
390/390 [==============================] - 15s 38ms/step - loss: 0.5192 - acc: 0.8145 - val_loss: 0.6818 - val_acc: 0.7682
Epoch 28/50
390/390 [==============================] - 14s 36ms/step - loss: 0.5147 - acc: 0.8163 - val_loss: 0.6869 - val_acc: 0.7748
Epoch 29/50
390/390 [==============================] - 14s 37ms/step - loss: 0.5112 - acc: 0.8190 - val_loss: 0.6954 - val_acc: 0.7722
Epoch 30/50
390/390 [==============================] - 14s 37ms/step - loss: 0.5044 - acc: 0.8184 - val_loss: 0.6906 - val_acc: 0.7751
Epoch 31/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4953 - acc: 0.8232 - val_loss: 0.6720 - val_acc: 0.7763
Epoch 32/50
390/390 [==============================] - 15s 37ms/step - loss: 0.4907 - acc: 0.8243 - val_loss: 0.6804 - val_acc: 0.7735
Epoch 33/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4859 - acc: 0.8251 - val_loss: 0.6959 - val_acc: 0.7714
Epoch 34/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4824 - acc: 0.8292 - val_loss: 0.6674 - val_acc: 0.7819
Epoch 35/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4783 - acc: 0.8295 - val_loss: 0.6821 - val_acc: 0.7768
Epoch 36/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4705 - acc: 0.8311 - val_loss: 0.6862 - val_acc: 0.7752
Epoch 37/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4761 - acc: 0.8299 - val_loss: 0.6736 - val_acc: 0.7794
Epoch 38/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4664 - acc: 0.8319 - val_loss: 0.7176 - val_acc: 0.7688
Epoch 39/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4593 - acc: 0.8338 - val_loss: 0.6744 - val_acc: 0.7813
Epoch 40/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4529 - acc: 0.8372 - val_loss: 0.6797 - val_acc: 0.7825
Epoch 41/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4588 - acc: 0.8362 - val_loss: 0.6849 - val_acc: 0.7787
Epoch 42/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4468 - acc: 0.8414 - val_loss: 0.6915 - val_acc: 0.7826
Epoch 43/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4443 - acc: 0.8420 - val_loss: 0.6815 - val_acc: 0.7753
Epoch 44/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4451 - acc: 0.8396 - val_loss: 0.7099 - val_acc: 0.7754
Epoch 45/50
390/390 [==============================] - 15s 37ms/step - loss: 0.4364 - acc: 0.8422 - val_loss: 0.7036 - val_acc: 0.7751
Epoch 46/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4419 - acc: 0.8411 - val_loss: 0.6748 - val_acc: 0.7855
Epoch 47/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4374 - acc: 0.8428 - val_loss: 0.6633 - val_acc: 0.7893
Epoch 48/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4299 - acc: 0.8453 - val_loss: 0.7186 - val_acc: 0.7707
Epoch 49/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4305 - acc: 0.8462 - val_loss: 0.6837 - val_acc: 0.7866
Epoch 50/50
390/390 [==============================] - 14s 37ms/step - loss: 0.4264 - acc: 0.8486 - val_loss: 0.6804 - val_acc: 0.7847
Model took 726.46 seconds to train
