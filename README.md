# u_net_image_seg
**Data Preparation:**
      1. I have downloaded ICDAR-2013 dataset which is publicly available.<br />
      2. Data preprocessing done like removing the duplicate file and removing the images for which "xml" file was missing.<br />
      3. After that i created mask for each image using "xml" file that contains the co-ordinate for each table in image. <br />
**Training:**<br />
      1. Then using "U-net" model, I have done the training and got the accuracy **4.48** percent. <br />
**Result:**:<br />
       *Accuracy*<br />
       ![Screenshot from 2023-02-06 16-28-35](https://user-images.githubusercontent.com/60688738/216956314-179aeeb5-0657-41c3-8484-e1987f4a3732.png)
       *Loss*<br />
       ![Screenshot from 2023-02-06 16-39-45](https://user-images.githubusercontent.com/60688738/216956694-ffd70ad4-3c35-4a71-8e36-d29115f8cee1.pn
**Future Work**<br />
      Increase the accuracy<br />
