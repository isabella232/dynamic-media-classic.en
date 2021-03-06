---
title: Managing the Trash folder
seo-title: Managing the Trash folder
description: null
seo-description: Learn how to manage the Trash folder.
uuid: 3992a5b8-1919-4924-b07d-7fb25565effd
contentOwner: admin
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/managing_assets
discoiquuid: 553c95fc-0a41-4f06-af50-a62bc1438149

---

# Managing the Trash folder{#managing-the-trash-folder}

Items that you delete from Dynamic Media Classic are moved to the Trash folder. They remain for seven days in this folder until they are restored or permanently deleted. You can examine deleted items by selecting the Trash icon located at the bottom of the Asset Library and viewing items in the Trash folder.

All users can restore items in the Trash folder to the folders from which they were deleted. All users can also empty the Trash folder of all its contents.

Deleting items from the Trash folder permanently deletes items from Dynamic Media Classic; items deleted from the Trash folder can no longer be restored. For information on setting up notifications for company administrators when assets are about to be automatically deleted from the Trash, see [Application General Settings](application-setup.md#general_settings).

>[!NOTE]
>
>Assets that have been moved to the Trash folder are still registered on Dynamic Media Classic. If you try to upload a file that has the same name as a deleted file in the Trash folder, Dynamic Media Classic treats the asset you want to upload as a duplicate asset. As such, a number is appended to its name.

## About the Trash folder {#about-the-trash-folder}

Deleting an item in a folder places the item in the Trash folder. The following happens when you delete an item and move it to the Trash folder:

* Although the item has been removed from your Dynamic Media Classic folders, its ID cannot be assigned to another asset while it remains in the Trash folder. If you try to upload an asset with the same name as a file in the Trash folder, Dynamic Media Classic appends a numeral to the name of the asset. 
* The item cannot be published. Even if the item was marked for publish when you deleted it, it is not published.
* The item remains in the Trash folder until it is restored, seven days pass, or someone chooses the Empty The Trash command. After seven days, an automatic clean-up operation permanently deletes the item.

## Restoring assets from the Trash folder {#restoring-assets-from-the-trash-folder}

It isn’t necessary for the person who deleted an asset to restore it; anyone can restore assets from the Trash folder. Assets that are restored are placed in the folders from which they were deleted. If these folders no longer exist, Dynamic Media Classic re-creates them, and the restored assets are placed in the re-created folders.

Follow these steps to restore assets from the Trash folder to the folders from which they were deleted:

1. Click the Trash icon to open the Trash folder.
1. Select the asset or assets you want to restore.
1. Choose File &gt; Restore From Trash.

## Permanently deleting assets in the Trash folder {#permanently-deleting-assets-in-the-trash-folder}

When you delete assets in the Trash folder, the assets are permanently deleted. Assets are automatically deleted from the Trash folder after seven days.

To permanently delete assets from the Trash folder, select the Trash icon, to open the Trash folder. Then delete individual assets or delete all the assets in the folder:

* **Deleting individual assets** Select the assets you want to permanently delete and click **[!UICONTROL File > Empty From Trash]**.

* **Deleting all assets** Click **[!UICONTROL File > Empty Trash]**.

>[!MORELIKETHIS]
>
>* [Delete assets](moving-renaming-deleting-assets.md#delete_assets)
