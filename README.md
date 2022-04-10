# tianchi_spinalAI_dection_competetion

this code is submit for the tianchi competetionSpark:"Digital body" AI Challenge.
link:https://tianchi.aliyun.com/competition/entrance/531796/introduction?lang=en-us 
dataset link: https://tianchi.aliyun.com/dataset/dataDetail?spm=5176.12281909.0.0.2b1935acBUEew8&dataId=79463#1 
the result is 27/3107 in final round at GPU track;
![image](https://user-images.githubusercontent.com/10162407/162633895-a784ac7d-f9ae-418c-83ca-6271ce825db5.png)


this code is base on the Unet and ResNet. For more design details,please refer to the following blog.
blog:https://blog.csdn.net/github_38148039/article/details/109562997

how to use this code:

1. datafile like this. you can download from tianchi platform.

   ![image](https://user-images.githubusercontent.com/10162407/162634295-10010e1c-8e57-4af7-8acc-b0066462dc19.png)

2. prepare the requirement.txt

   >numpy==1.18.1
   >pandas==1.0.4
   >imgaug==0.4.0
   >matplotlib==3.2.1
   >visdom==0.1.8.9
   >torchsummary==1.5.1
   >scikit_image==0.17.2
   >tqdm==4.46.1
   >Pillow==7.2.0
   >SimpleITK==1.2.4
   >torchvision~=0.6.1
   >scikit-image~=0.17.2

3. run `code/train.py` ,set the correct file path and name and choice to display the viz.
4. run `code/testA_submit.py` .

this is all.  please makes a star if  you like my contribution.
