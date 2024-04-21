# CFC
A Face Anti_spoofing Algorithm Based on Multi_head Attention and Convolutional Neural Network


# CFC
A Face Anti_spoofing Algorithm Based on Multi_head Attention and Convolutional Neural Network

A Simple and Efficient Face Anti-spoofing Algorithm Based on Single Modal

 The detail in our paper: A Simple and Efficient Face Anti-spoofing Algorithm Based on Single Modal
 
  The average classification error rate (ACER) on the validation set (CASIA-SURF) is only 0.00333, TPR@FPR =10E-4 reaches 0.9880; The ACER on the test set (CASIA-CeFA) is 0.03427, TPR@FPR =10E-4 reaches 0.8970.

  
  CFC：（Verification results）TPR@FPR=10-2: 0.9990	TPR@FPR=10-3: 0.9947	TPR@FPR=10-4: 0.9880；TN:6759  FP:9  FN:16  TP:2984  APCER:0.001330  NPCER:0.005333  ACER:0.00333156

  
   CFC：test set:CASIA-CeFA;test results:TPR@FPR=10-2: 0.9943	TPR@FPR=10-3: 0.9712	TPR@FPR=10-4: 0.8970;TN:2630  FP:186  FN:7  TP:2808  APCER:0.066051  NPCER:0.002487  ACER:0.03426891

   
   CFC：test set:CASIA-SURF;test results:TPR@FPR=10-2: 0.9929	TPR@FPR=10-3: 0.9598	TPR@FPR=10-4: 0.8260;TN:41390  FP:294  FN:168  TP:17331  APCER:0.007053  NPCER:0.009601  ACER:0.00832681


   [CASIA-SURF Dataset](https://arxiv.org/abs/1812.00408)[2]
   How to download CASIA-SURF dataset?

1.Download, read the Contest Rules, and sign the agreement,[link](http://www.google.com/url?q=http%3A%2F%2Fwww.cbsr.ia.ac.cn%2Fusers%2Fjwan%2Fdatabase%2FCASIA-SURF_agreement.pdf&sa=D&sntz=1&usg=AFQjCNHFuTTHdLXoJbtuuxf4nvgT8A4Nzw)

2. Send the your signed agreements  to: Jun Wan, jun.wan@ia.ac.cn

   
Train the model
train CFC
Set opt file:
opt.exp_name = 'cfcms_d'
opt.net_type = 'cfcms'
opt.img_type = 'depth'
     
nohup python main_new.py  
