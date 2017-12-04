# Motion House Sync for Unity
This is the Unity plugin specifically made for <a href = "http://www.motionhouse.co.kr/sub/sub_04_01.php"> Motion House</a>.

Pre-Requisite
---
System-requirement: Windows PC<br>
Motion-House SDK is required<br>

Instruction
---
<h3>1. Put dependent Dll file </h3>
Place the mpi.dll and mpi64.dll to root directory of Unity project folder.

<h3>2. Import the plugin to Unity project </h3>
/Plugins/MotionHouseSDK32Release.dll<br>
/Plugins/MotionHouseSDK64Release.dll<br>
/MotionHouseLink/MHSyncObject.cs<br>
/MotionHouseLink/MotionHouseWrapper.cs<br>

<h3>3. Applying the script </h3>
MHSyncObject: Syncing the rotation of the transform component. It is syncing with Motion House device each frame.<br>
Put this script to the game object that you want to sync.

<b>* MHSyncObject MUST EXIST in one game object of the project scene.</b>

<h3>4. Modifying the script </h3>
Editing the MHSyncObject script for customization

<h3>5. Important information when building the project </h3>
Place mpi.dll and mpi64.dll in the build directory which has the .exe executable file.
