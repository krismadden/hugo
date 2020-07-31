---
title: 'SD Card'
date: 2019-02-11T19:27:37+10:00
draft: false
weight: 4
---

<!--more-->



####  How to format the SD card?
With 64 GO SD card, Create two partitions with the first one containing 95% of the memory area and the second one 5%. The card should be formatted in the NTFS File System, and the partitions should be created in a fixed order (audio first, accelerometer second). The table below gives the names and sizes of the partitions that should be created according to your SD card size.



Partition| Name of partition| partition_size | partition_type| size_unity_allocation
--- |--- |--- | --- | ---
Partition 1 | BL_AUDIO|60.8GB |EXFAT| 64Ko 
Partition 2 | BL_MOTION |3.2GB |FAT32| 32Ko 

#### How to create a partition on a new SD card?
- **Tutorial**
  [here](xxx) is a tutorial.

- **OR Follow the steps below**
  -  Download the SD card image already partitioned [SDCard image](/images/img.zip).
  - **For MacOS/OS X and Linux**

    1.  Download and Install Etcher from https://etcher.io .
    2.  Open Etcher and click "Select Image" to choose the image file you already downloaded.
    <center>![Super wide](/images/sd1.png)</center>
    3. Choose SD Card as Drive.

    4. Click Flash.
    5. When the process is completed, eject and insert the SD card into the BabyLogger and power it up.
- **For Windows**

    1. Download the [Win32](https://sourceforge.net/projects/win32diskimager/) application for flashing the SD card
    2. Select your device (SD card) 
        
        <center>![Super wide](/images/sd2.png)</center>
    3. Locate the downloaded disk image
    
        <center>![Super wide](/images/sd3.png)</center>
    4. Click Write and wait for the wriing to be completed
   
        <center>![Super wide](/images/sd4.png)</center>
    5. When the process is completed, eject and insert the SD card into the BabyLogger and power it up.
