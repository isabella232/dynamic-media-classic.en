---
title: Creating a Mixed Media Set
seo-title: Creating a Mixed Media Set
description: null
seo-description: Learn how to create a Mixed Media Set.
uuid: a0c6e5fa-7a85-4376-b9a3-b72ae63d3d95
contentOwner: admin
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
discoiquuid: 0ff9e763-897c-4ba5-b606-a95d5e45f35e

---

# Creating a Mixed Media Set{#creating-a-mixed-media-set}

Create a Mixed Media Set when you want to combine multiple types of viewers in one presentation. Make sure your files, Image Sets, Swatch Sets, and Spin Sets are ready to publish before you add them to the Mixed Media Set.

![Mixed Media Set](/help/assets/mm_mixed_media_set.png) 

## Create a Mixed Media Set {#create-a-mixed-media-set}

When you create a set, the **Publish after save** option affects the set and set members in the following ways:

|“Publish after save” option selected before saving?|State of set after saving|State of set members after saving|
|--- |--- |--- |
|Yes|Published|Published|
|No|Unpublished|Set members retain their published or unpublished state.|

See also [Manually publishing assets](publishing-files.md#manually_publishing_assets) and [Manually unpublishing assets](publishing-files.md#manually_unpublishing_assets).

**To create a Mixed Media Set**

1. Click **Build** &gt; **Mixed Media Sets**.
1. Drag the videos, Image Sets, Spin Sets, and swatches from the Asset Library to the Mixed Media Set screen.

   >[!NOTE]
   >
   >Mixed Media Sets do not support assets with filenames that contain any of the following characters: ( ) { }.

1. Do any of the following:

    * To add a soundtrack, drag an audio file from the Asset Library to the Soundtrack box. The soundtrack plays while images are displayed. It stops when video is played.
    * To change the order of sets, drag them to new locations on the Mixed Media Set screen. The order of sets on the screen determines the left-to-right order in which users see sets in the Mixed Media Set Viewer.
    * (Optional) To add a custom thumbnail to represent a video in the Viewer, drag an image file from the Asset Library to the Thumbnail placeholder box.

1. Near the lower-right corner of the page, ensure that **Publish after save** is selected (default).
1. Click **Save**, select a folder for storing your Mixed Media Set, enter a name for the set, and click **Save**.

   Click **Preview** to see what your combo Image Set looks like in an Image Set Viewer.

## Edit a Mixed Media Set {#edit-a-mixed-media-set}

You can edit a Mixed Media Set. If you want to edit a set within a Mixed Media Set, open that set separately, edit it, and save it. The edits appear in the Mixed Media set.

Depending on whether you edit a published or an unpublished set, the **Publish after save** option affects the set and set members in the following ways:

|Set already published?|“Publish after save” option selected before saving your edit?|State of set after saving|State of set members after saving|
|--- |--- |--- |--- |
|Yes|Yes|Published|Published|
|Yes|No|Published|Existing set members retain their published state.Any new set members that you added during your edit retain their published or unpublished state.|
|No|Yes|Published|Published|
|No|No|Unpublished|Existing set members and any new set members that you added during your edit retain their published or unpublished state.|

See also [Manually publishing assets](publishing-files.md#manually_publishing_assets) and [Manually unpublishing assets](publishing-files.md#manually_unpublishing_assets).

**To edit a Mixed Media Set**

1. Click the Mixed Media Set’s rollover **Edit** button. 
1. Do any of the following:

    * To remove items, select them and click **Delete**.
    * To reorder items, drag them to new locations.

1. When you are finished editing the set, near the lower-right corner of the page, ensure that **Publish after save** is selected (default).
1. Click **Save** or **Save As**.

## Deleting a Mixed Media Set {#deleting-a-mixed-media-set}

When you delete a set, the set itself is moved to the Trash. However, the members (or “children”) within that set are not affected; instead, they each retain their existing published or unpublished state.

See also [Manually publishing assets](publishing-files.md#manually_publishing_assets) and [Manually unpublishing assets](publishing-files.md#manually_unpublishing_assets).

**To delete a Mixed Media Set**

1. In the Grid View, List View, or Details View, select one or more Mixed Media Sets.
1. On the Global Navigation Bar, click **File** &gt; **Delete** &gt; **Delete**.

