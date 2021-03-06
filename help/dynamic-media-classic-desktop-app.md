---
title: Adobe Dynamic Media Classic desktop app - Now available
seo-title: Adobe Dynamic Media Classic desktop app - Now available
description: null
seo-description: Learn more about Dynamic Media Classic desktop app.
contentOwner: admin
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/introducing_adobe_dynamic_media_classic

---

# Now available: Adobe Dynamic Media Classic desktop app {#dynamic-media-classic-desktop-app}

Dynamic Media Classic users now have access to a new desktop app experience that no longer relies on Adobe Flash technology in the browser. 

This new app is now available for Windows and macOS.

>[!IMPORTANT]
>
>We recommend that you install the new Adobe Dynamic Media Classic desktop app by October 1, 2020. Doing so will ensure you have a smooth transition before Adobe Flash Player is deprecated on December 31, 2020. On that date, you will no longer be able to log on to the browser version of Adobe Dynamic Media Classic user interface, labeled as Dynamic Media Classic in the product.

See the FAQ for the [New Dynamic Media Classic sign in experience now available.](/help/new-ui-2020.md)

## System requirements for Adobe Dynamic Media Classic desktop app {#system-requirements-dmc-app}

Adobe Dynamic Media Classic desktop app is compatible with the following operating systems:
* macOS X 10.10 or newer.
* Windows 7 or newer.

## Download and install Adobe Dynamic Media Classic desktop app {#installation-dmc-app}

1. Uninstall any older Dynamic Media Classic desktop app versions on your system.

1. Download the latest installer for Adobe Dynamic Media Classic desktop app.

    * [macOS (.dmg) &ndash; Download.](http://download.macromedia.com/dynamic-media-classic/20.20.1/adobe-dynamic-media-classic-20.20.1.dmg)
    * [Windows (.exe) &ndash; Download.](http://download.macromedia.com/dynamic-media-classic/20.20.1/adobe-dynamic-media-classic-20.20.1.exe)

1. Do one of the following based on the installer you downloaded.

    * **For macOS** &ndash; In the **[!UICONTROL Drag & drop to install]** dialog box, drag **[!UICONTROL Adobe Dynamic Media Classic]** and drop it onto **[!UICONTROL Applications]**.

        ![Drag and drop install on macOS](/help/assets/dragondrop-install1.png)

    * In the **[!UICONTROL Applications]** folder, tap the Adobe Dynamic Media Classic icon.
    * In the dialog box, tap **[!UICONTROL Open]** to open the Adobe Dynamic Media Classic desktop app.

        ![Open downloaded app](/help/assets/open-dmclassicapp1.png)

    * **For Windows** &ndash; Run the installer binary and follow the on-screen instructions to install the desktop app.

1. When you open the application, the new Adobe Dynamic Media Classic Sign In page is displayed:

    ![Dynamic Media Classic sign in](/help/assets/dmclassic-login1.png)

1. Use the same credentials as your browser credentials to sign in to Adobe Dynamic Media Classic.

    For the **[!UICONTROL Server]** to use, see the following mapping for the production environment:

    | Browser URL | Desktop app server name |
    |---|---|
    | https://s7sps1.scene7.com/ | NA (North America) production |
    | https://s7sps3.scene7.com/ | EMEA (Europe, Middle East, and Africa) production |
    | https://s7sps5.scene7.com/ | APAC (Asia-Pacific) production |
 
1. Post the login UI, you will notice the familiar browser UI experience. You can carry your day to day activity as usual now on the desktop app UI.

## Video walk-through on using Dynamic Media Classic Desktop App

Watch a [video walk-through on using Dynamic Media Classic Desktop App](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/dynamic-media/dynamic-media-classic-desktop-application.html) (Length: 2 minutes 36 seconds). 

## Known limitations in Dynamic Media Classic 
 
**_Applies to Windows only &ndash; Is there a limitation on the number of files that can be uploaded through the desktop app UI?_**<br>Yes, a maximum of 150 files can be uploaded at a time by way of the desktop app UI.

**_Applies to Windows and macOS &ndash; How do I switch between companies?_**<br>To switch between companies, do the following:
* In the Dynamic Media Classic app, select the new company from the company drop-down list.
* When the pop-up appears, tap **[!UICONTROL OK]** to sign out and close the app.

    ![Restart the app to use the new company](/help/assets/dmclassic-new-company1.png)
* Restart Dynamic Media Classic, then sign in as usual to work with the new company.

## Tips and Tricks 

**_I am unable to see Media Cart panel on the landing page of Dynamic Media Classic._**<br>In Dynamic Media Classic, tap **[!UICONTROL Setup > Personal Setup]**. In the Browser section, make sure **[!UICONTROL Show MediaPortal Features]** is selected (checked). Tap **[!UICONTROL Save > Close]**.
 
**_Publish state (green indicator) of an asset is not reflected correctly._**<br>In the browser UI, a re-login to the UI was required to see the correct publish state of assets. In the desktop app, we have introduced a **[!UICONTROL Refresh]** icon on the toolbar, to the right of the **[!UICONTROL Select None]** button. Tap the **[!UICONTROL Refresh]** icon to see the latest status of all the assets on the given page. No re-login required as with the browser UI.

![Refresh icon](/help/assets/refresh-icon1.png)
*Refresh icon*
 
**_I don't see batch set presets working in the desktop app._**<br>Tap **[!UICONTROL Upload > Job Options > Batch Set Presets]**. Ensure the relevant **[!UICONTROL Batch Set Preset]** is enabled. Click **[!UICONTROL Save and Submit upload]**. 
