# Meta Work Setup Instructions

This APK is already being hosted on GitHub in a public way. To use this APK in your Meta Work Managed environment please follow the instructions below.

## Access Meta Device Manager

Login to your Meta Work Account and proceed to the [device manager area of Meta Work](devicemanager.meta.com), on the left hand toolbar look for the 'Apps & Content' section.

![Meta Device Manager](./Images/Meta_App_000.png)

### Add an Application

We are now going to add an application that is publicly hosted through the Meta Work Managed apps section.

In the upper right corner click the 'Add app' button and look for **'Externally hosted'**.
![Meta Externally Hosted](./Images/Meta_App_001.png)

A pop up window with some details are now needed for you to fill out.

![Meta Externally Hosted Page 1 of 4](./Images/Meta_App_002.png)

The application name, link, and SHA256 will be provided for you for each apk build. For our example purposes please see that information below

* Version: 0.6.5
* Updated 5/19/2026 2:35AM
* Application Name: TellVR_F1M1Setup_S2
* APK Link: [https://github.com/ODU-ERI-Lead/TellVR_Testing/releases/download/0.6.6/F1M1_Setup_S1_S2.apk](https://github.com/ODU-ERI-Lead/TellVR_Testing/releases/download/0.6.6/F1M1_Setup_S1_S2.apk)
* SHA256: 5a0944d7c7a63f040f14deb8fc4ba2048ef2e1faced14c7d8c627f862b560317
* Module: French Module 1
* Scene(s): Setup, Unpacking, Test Plane

![Meta Externally Hosted Page 2 of 4](./Images/Meta_App_003.png)

You will also be provided with an Icon file and a Logo file. The icon will be 512x512 and have the module and scene index on it. The logo file will probably only vary between French and Spanish and generally be the same.

![Meta Externally Hosted Page 3a of 4](./Images/Meta_App_004.png)

Banner Image: https://github.com/ODU-ERI-Lead/TellVR_Testing/blob/main/MetaLogos/FrenchOneBannerV2.png
![Banner Image](https://github.com/ODU-ERI-Lead/TellVR_Testing/blob/main/MetaLogos/FrenchOneBannerV2.png)

Logo Image: https://github.com/ODU-ERI-Lead/TellVR_Testing/blob/main/MetaLogos/F1M1S1thruS2.png
![Logo Image](https://github.com/ODU-ERI-Lead/TellVR_Testing/blob/main/MetaLogos/F1M1S1thruS2.png)

![Meta Externally Hosted Page 3b of 4](./Images/Meta_App_005.png)

For the Manage updates section, just leave automatic on and you should be done.

If you noticed compatibility errors - just ignore these as we are using some SDK tools from Meta that throw up some warning flags tied to devices in a shared mode use case.

![Meta Externally Hosted Finished](./Images/Meta_App_006.png)
