## NDVI Tree Crown Detection
This is a simple sattelite imagery tree crown segmentation which uses NDVI treshold to segment crowns. at the end it returns crown masks which is useful for data labeling and ground truth production.If the loaded file is inappropriate, you can push "Delete File" button and remove it from files directory. If NDVI doesn't work precise fore tree crown segmentation, you can push "Manual" button. With this "MANUAL_" will be added to begining of your file name like: "MANUAL_patchxxxx.tif" , then you can sort these files and lable them manually with other platforms. Note that by default, it shows normalized RGB image. if you wanna see images with stretched bands, you should change "rgb_image" with "R_I" in this code. stretching bands might be useful in some images.

![Figure_3](https://github.com/user-attachments/assets/05500f1e-ba4b-4958-ae11-fee6b979b29f)

## delinated Tree Crowns:

![Screenshot (715)](https://github.com/user-attachments/assets/f4c87fa1-8146-4c42-8612-b6ee59a53bc1)



This simple code allows you to make binary masks of tree crowns. run this code in your repo and set the treshhold. after you push the save button, the final mask of that image will be saved in maks directory and the original image will be moved to masked_images directory.
