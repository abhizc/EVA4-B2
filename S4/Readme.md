# MNIST implementation in Pytorch

Total Parameters Used:
Highest Accuracy acheived:
Number of Epocs: *20*

## Model Summary

----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1            [-1, 8, 28, 28]              80
            Conv2d-2            [-1, 8, 28, 28]             584
       BatchNorm2d-3            [-1, 8, 28, 28]              16
         MaxPool2d-4            [-1, 8, 14, 14]               0
            Conv2d-5           [-1, 16, 14, 14]           1,168
            Conv2d-6           [-1, 16, 14, 14]           2,320
       BatchNorm2d-7           [-1, 16, 14, 14]              32
         MaxPool2d-8             [-1, 16, 7, 7]               0
            Conv2d-9             [-1, 32, 5, 5]           4,640
           Conv2d-10             [-1, 10, 3, 3]           2,890
        AvgPool2d-11             [-1, 10, 1, 1]               0
================================================================
Total params: 11,730
Trainable params: 11,730
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.00
Forward/backward pass size (MB): 0.24
Params size (MB): 0.04
Estimated Total Size (MB): 0.29


## Epoch Logs

0%|          | 0/469 [00:00<?, ?it/s]/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:29: UserWarning: Implicit dimension choice for log_softmax has been deprecated. Change the call to include dim=X as an argument.
loss=0.15335333347320557 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 26.95it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0634, Accuracy: 9801/10000 (98.01%)

loss=0.12426242232322693 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 26.98it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0657, Accuracy: 9796/10000 (97.96%)

loss=0.09512967616319656 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 26.61it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0402, Accuracy: 9870/10000 (98.70%)

loss=0.017879093065857887 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 26.76it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0348, Accuracy: 9894/10000 (98.94%)

loss=0.017948204651474953 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 26.89it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0270, Accuracy: 9919/10000 (99.19%)

loss=0.024196987971663475 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 26.90it/s]
  0%|          | 0/469 [00:00<?, ?it/s] 
Test set: Average loss: 0.0306, Accuracy: 9906/10000 (99.06%)

loss=0.0011209944495931268 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 26.97it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0392, Accuracy: 9885/10000 (98.85%)

loss=0.032927896827459335 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 27.12it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0293, Accuracy: 9902/10000 (99.02%)

loss=0.06968580186367035 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 27.01it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0337, Accuracy: 9887/10000 (98.87%)

loss=0.0018402686109766364 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 26.87it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0298, Accuracy: 9907/10000 (99.07%)

loss=0.004850298166275024 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 27.19it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0255, Accuracy: 9910/10000 (99.10%)

loss=0.011002838611602783 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 26.94it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0436, Accuracy: 9863/10000 (98.63%)

loss=0.0010633220663294196 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 27.03it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0281, Accuracy: 9917/10000 (99.17%)

loss=0.0002040565013885498 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 27.05it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0274, Accuracy: 9909/10000 (99.09%)

loss=0.02293277718126774 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 27.08it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0269, Accuracy: 9919/10000 (99.19%)

loss=0.22301773726940155 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 27.05it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0310, Accuracy: 9915/10000 (99.15%)

loss=0.0052879503928124905 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 27.19it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0333, Accuracy: 9900/10000 (99.00%)

loss=0.0010468065738677979 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 27.03it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0328, Accuracy: 9912/10000 (99.12%)

loss=0.006291677709668875 batch_id=468: 100%|██████████| 469/469 [00:17<00:00, 26.98it/s]

Test set: Average loss: 0.0272, Accuracy: 9920/10000 (99.20%)

