---
title: Cropping an image
seo-title: Cropping an image
description: null
seo-description: Learn how to crop an image.
uuid: 84f199de-cbfc-4d06-877f-6e9148e82e15
contentOwner: admin
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/master_files
discoiquuid: 99dfa476-4f11-4569-a27e-a76ed7787674

---

# Cropping an image{#cropping-an-image}

You can crop images in the Dynamic Media Classic. The system retains information about images that were cropped so you can restore them to their original state. You can also crop an image and save the cropped version under a new name.

You can crop an image to remove white space around it, or crop an area of the image.

>[!NOTE]
>
>After you crop, you can click the Save As button and save a cropped version of the image under a different name. In the Save As window, choose Save As New Master to save a second copy of the image. Choose Save As Addition View Of Master to save the original and its cropped version under a different name. Choose Replace Original to delete the original file from which you cropped your image. Then enter a name for the image and select the Submit button.

## Crop to remove white space around an image {#crop-to-remove-white-space-around-an-image}

You can crop off the transparent or solid-color pixels from the edge of an image.

1. To crop an image, click its rollover Edit button and choose Crop, or display it in the Browse Panel in Detail view and click the Crop button. The Crop Editor screen opens.
1. Do one of the following:

    * To trim color pixels, select the Trim menu and choose Color. The Auto Crop By Color dialog box appears. Select the Corner menu and choose a corner with the background color to crop away. Then enter a Tolerance setting from 0 through 1. The 0 setting crops pixels only if they exactly match the color you selected in the corner of the image. Numbers closer to 1 allow for more color difference. Select the Crop button.
    * To trim transparent pixels, select the Trim menu and choose Transparent. The Auto Crop By Transparency dialog box appears. Enter a tolerance setting from 0 through 1. The 0 setting crops crop pixels only if they are totally transparent. Numbers closer to 1 allow for more transparency. Select the Crop button.

1. Click **Save**.

>[!NOTE]
>
>To restore an image to its original state after you’ve cropped it, display the image in the Crop Editor screen and select the Reset button.

## Select an area to crop {#select-an-area-to-crop}

1. To crop an image, click its rollover Edit button and choose **Crop**, or display it in the Browse Panel in Detail view and click **Crop**.

1. In the Crop Editor window, place the part of the image you do not want to crop in the crop box. What appears inside the box remains when you click **Save** and crop the image.
1. To adjust the crop area, do one of the following:

    * Drag a side or corner of the box. Hold down the Shift key as you drag to change size but maintain the aspect ratio (the shape) of the crop box.
    * Enter pixel measurements in the Size boxes.
    * Drag to move the crop box. Move the pointer inside the boundary of the box. When you see the four-headed arrow, drag the box to a new location on the image.

1. Click **Save**.

>[!NOTE]
>
>To restore an image to its original state after you’ve cropped it, display the image in the Crop Editor screen and select the Reset button.

>[!MORELIKETHIS]
>
>* [Image editing options at upload](image-editing-options-upload.md#image-editing-options-at-upload)
>* [Cropping white space from a PDF file](pdfs.md#cropping_white_space_from_a_pdf_file)
>* [Cropping from the sides of PDF pages](pdfs.md#cropping_from_the_sides_of_pdf_pages)
