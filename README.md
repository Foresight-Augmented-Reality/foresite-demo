# Hear2There internal demo

Use this project to verify the SDK can be packaged and our sample code works

## Get this Repo
Download a copy using the Code button on the home page
<img width="1492" alt="image" src="https://github.com/user-attachments/assets/30daea40-5942-4831-8ce9-8c6cc30d7aff" />

## Open This project in Xcode.
Verify you can select a signing profile to install on an iPhone. If you don't have this you can use the Simulator, but it is challenging to get the simulator to get full control of the bluetooth smetimes to scan. 
<img width="1512" alt="image" src="https://github.com/user-attachments/assets/fa6f05c8-57c1-4243-89a3-2d8380a9b966" />


## Verify Permissions
Apps that use bluetooth need to declare it to the user to offer the permission screen. Make sure there's a text value in the plist here
<img width="1512" alt="image" src="https://github.com/user-attachments/assets/591952e6-06f7-491d-9177-018b5307b3f2" />

## Drag and Drop the Framework In
Grab the most recent [Release](https://github.com/Foresight-Augmented-Reality/foresight-sdk/releases). Drag it into the Xcode Project next to your app code
<img width="1512" alt="image" src="https://github.com/user-attachments/assets/30c6069d-cb5c-413e-8578-c2be11594b05" />

## Make sure the demo app has the Framework as a dependency 
Should Say Embed and Sign
<img width="1512" alt="image" src="https://github.com/user-attachments/assets/87a257eb-36fe-457a-8ab2-db763aa111a9" />

## Make sure the Content View UI has our import, classes, and code in
<img width="1512" alt="image" src="https://github.com/user-attachments/assets/724eba6f-ba99-46a0-92ef-c0eb3d4f95f2" />



