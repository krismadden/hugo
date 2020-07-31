---
title: 'Decrypting the data'
date: 2019-02-11T19:27:37+10:00
weight: 5
---


All data recorded with the BabyLogger are encrypted for data protection. If the logger is lost, nobody except for the registered user will be able to decrypt the data. For that reason, do not share the downloaded software as well as the security key.
<!--more-->
#### Key management
- If you haven't already downloaded your keys during the 'Environment installation' process, you should go [here](http://coml.lscp.ens.fr/babylogger/). Enter the **username** and the **code** provided in the email to download **Key** folder with all the keys associated with your loggers. Then copy that 'Key' folder into the 'BabyLogger' folder.
  
**IMPORTANT: you should not attempt to modify or remove anything in the 'Key' folder. If you encounter any problem, re-download the keys and make sure that you are using the correct set of loggers (you can find the logger's ID in the accelerometer files).**

#### How to decrypt the BabyLogger data?
You must decrypt all data from one logger first and finish the process before decrypting other files. Otherwise, you will overwrite the raw files from the current logger because currently, all raw files share the same names regardless of the logger used) .

 1. Launch the decryption process by choosing one of these 2 options:
  - A) Double-click on the 'decrypt app' icon (if you encounter any problem, see the FAQ section).
  - B) Open a terminal `Ctrl+Alt+T`
       - Go to the path of the installed 'BabyLogger' folder.
       - Type the following command: `./decrypt`

 2. The decryptiion process will save the audio (wavs) and accelerometer data in the **Decrypt_Data** folder.
 3. You can then copy them for backup or move them for further processing. The files have now a unique name (associated with the logger ID and date).
 4. Delete all remaining files in the **Raw_data** folder.
 5. Delete all files from both partitions of the MicroSD card.

**NOTE: All data must be transferred from the MicroSD, processed and then deleted before the logger is in recording mode again.**


#### The decrypted files
The decrypted files can be found in the **Decrypt_Data** folder. You will find three types of files :

 1. **Audio files** (XX-Audio.wav): the audio files were recorded with a frequency of 16kz, 16bits and 4 channels. their duration is no longer than 30mins long.
    - Audio file example: `0002-20200115-20_40_07-Audio.wav`
 2. **Actimetry files**  (XX-Acti.txt):
    - Actimetry file example: `0002-20200115-20_40_07-Acti.txt`
 3. **Meta data files** (XX-Data.txt):
    - Meta data file example: `Actimetry file example: 0002-20200115-20_40_07-Data.txt`