# Meta Work Setup Instructions

This APK is already being hosted on GitHub in a public way. To use this APK in your Meta Work Managed environment please follow the instructions below.

## Access Meta Device Manager

Login to your Meta Work Account and proceed to the [device manager area of Meta Work](devicemanager.meta.com), on the left hand toolbar look for the 'Apps & Content' section.

![Meta Device Manager](Meta_App_000.png)

### Add an Application

We are now going to add an application that is publicly hosted through the Meta Work Managed apps section.

In the upper right corner click the 'Add app' button and look for **'Externally hosted'**.
![Meta Externally Hosted](Meta_App_001.png)

A pop up window with some details are now needed for you to fill out.

![Meta Externally Hosted Page 1 of 4](Meta_App_002.png)

The application name, link, and SHA256 will be provided for you for each apk build. For our example purposes please see that information below

* Application Name: TellVR_F1M1Setup_S2
* APK Link: https://github.com/ODU-ERI-Lead/TellVR_Testing/releases/download/V3/F1M1_Setup_S1_S2.apk
* SHA256: b4bd357acb0335351b82a061daaab1129e869b0eccc578bcbbdc64016f0aacc4
* Module: French Module 1
* Scene(s): Setup, Unpacking, Airplane

![Meta Externally Hosted Page 2 of 4](Meta_App_003.png)

You will also be provided with an Icon file and a Logo file. The icon will be 512x512 and have the module and scene index on it. The logo file will probably only vary between French and Spanish and generally be the same.

![Meta Externally Hosted Page 3a of 4](Meta_App_004.png)
![Meta Externally Hosted Page 3b of 4](Meta_App_005.png)

For the Manage updates section, just leave automatic on and you should be done.

If you noticed compatibility errors - just ignore these as we are using some SDK tools from Meta that throw up some warning flags tied to devices in a shared mode use case.

![Meta Externally Hosted Finished](Meta_App_006.png)