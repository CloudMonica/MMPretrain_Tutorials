- 训练结果：  
06/11 10:03:50 - mmengine - INFO - Epoch(val) [100][55/55]    accuracy/top1: 96.5596  accuracy/top5: 99.0826  data_time: 0.0015  time: 0.0092
06/11 10:03:50 - mmengine - INFO - The previous best checkpoint /root/autodl-tmp/project/data_fruit/exp/best_accuracy_top1_epoch_70.pth is removed
06/11 10:03:52 - mmengine - INFO - The best checkpoint with 96.5596 accuracy/top1 at 100 epoch is saved to best_accuracy_top1_epoch_100.pth.
Training finished successfully. 
- 测试集结果：
Loads checkpoint by local backend from path: exp/best_accuracy_top1_epoch_100.pth
06/12 09:53:14 - mmengine - INFO - Load checkpoint from exp/best_accuracy_top1_epoch_100.pth
06/12 09:53:16 - mmengine - INFO - Epoch(test) [10/57]    eta: 0:00:11  time: 0.2442  data_time: 0.0553  memory: 251  
06/12 09:53:16 - mmengine - INFO - Epoch(test) [20/57]    eta: 0:00:04  time: 0.0073  data_time: 0.0003  memory: 251  
06/12 09:53:17 - mmengine - INFO - Epoch(test) [30/57]    eta: 0:00:02  time: 0.0079  data_time: 0.0003  memory: 251  
06/12 09:53:17 - mmengine - INFO - Epoch(test) [40/57]    eta: 0:00:01  time: 0.0075  data_time: 0.0003  memory: 251  
06/12 09:53:17 - mmengine - INFO - Epoch(test) [50/57]    eta: 0:00:00  time: 0.0072  data_time: 0.0002  memory: 251  
06/12 09:53:17 - mmengine - INFO - Epoch(test) [57/57]  accuracy/top1: 93.5841  accuracy/top5: 99.1150  data_time: 0.0002  time: 0.0125
