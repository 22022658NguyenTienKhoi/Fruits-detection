![image.png](attachment:19efb003-49a6-43cb-ad0c-0c83edb549ad.png)
With YOLO11 trained from scratch, mAP on test is 0.72, the pretrained version achive 0.76 with same epoch training, the YOLO12 is slightly better at 0.77. The detr is a pretrained version called with huggingface transformer, it only achieve 0.53, yet I only trained it for 50 epochs. I also tried one shot prompt with DINO, and enhance the prompt using Gemma model to label fruits in image, however, may this model still needs to be finetuned.  
All experiment is infered with confidence threshold of 0.25.
