---
title: "Environment Installation"
weight: 220
description: >
  Use hugo shortcodes to quickly compose site pages.
---

This section allows the user to set up the environment for the BabyLogger to work in the best way.


<!--more-->
### Download the BabyLogger software
   - Download the BabyLogger's Software Package corresponding to your computer's operating system.
     - Click [Linux](/images/BabyCloud.zip) .
     - Click  [MacOs](/images/BabyCloud.zip) .
     - Click  [Windows](/images/BabyCloud.zip). 
   - Unzip the downloaded BabyLogger Softawre Package onto the computer . This step will create a **BabyLogger** folder.
   - Inside this folder, you will see three important folders:  
  
      - **Raw_Data** : it will contain the temporary encrypted  data.
      - **Decrypted_Data** : it will contain the decrypted data
      - **Scripts** :it contains all the needed scripts.
      - **Keys**: it will contain the keys to decrypt the data. You have to go [here](http://coml.lscp.ens.fr/babylogger/) and enter the **username** and **code** given on the email to download a **'Keys'** folder, with all the keys generated for your loggers. Please copy this folder into the **'BabyLogger'** folder.
  

### Run the provided script to download all the required utilities
 - Open a terminal `Cntrl+Alt+t` and go to the **Scripts** folder and run the script `./softwares` or `sh softwares.sh`.
The utilities downloaded will be: **SFTP protcole**, **FileZilla (FTP Client)**, **Python3**, **HomeBrew**, **Sox**.

**<p style="color:red">NOTE</p>**
    Make sure that your computer has the required security protection (antivirus, hard drive encryption, password logins).
     As your computer will contain sensitive data collected with families, you are responsible for their data protection."

