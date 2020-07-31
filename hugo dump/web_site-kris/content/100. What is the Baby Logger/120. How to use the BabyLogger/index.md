---
title: "How to use the BabyLogger"
weight: 120
description: >
  Use hugo shortcodes to quickly compose site pages.
---

Differents steps to explain how to uses the BabyLogger.
<!--more-->


<!-- 

remove this and put the navigation in the sidebar

- [How to use the BabyLogger](#BabyLogger)
- [Step1: Start the logger](#Step1)
- [Step2: Record](#Step2)
- [Step3: Stop the logger](#Step3)
- [Step4: Transfert](#Step4)
- [Step5: Decrypt process](#Step5)
- [Step6: Recharge the logger](#Step6) -->


<!--more-->


### What is the BabyLogger?
The BabyLogger is very simple to use. It has a single button used to power on (short press) and to turn it off (long press). The different states of the BabyLogger are indicated via two LEDs ( <span style="color:green">**GREEN** </span> &  <span style="color:red">**RED** </span> ). 

The BabyLogger includes 2 parts: a main body and a cover. Removing the cover gives access to the SD card and the charger plug (micro USB).

To use the BabyLogger on recording mode, you have to put on its cover, insert it in the breast pocket of the participant, with the top of the cover facing up, and the three microphones facing outside.

The BabyLogger has a 24 hour capacity of continuous recording (both in battery and in data). After each recording session, you’ll have to transfer the data to your computer through the SD card, delete all files on the SD card, and recharge your BabyLogger.

### <a name="Step1"></a>Step1 . How to start the logger?

- Press briefly on the power button.
- Immediately after powering on, the device is going through a series of internal checks (battery, SD card) that last a few seconds. 
- The device is ready for use if:
  - the <span style="color:green">**GREEN LED** </span> stays still and the <span style="color:red">**RED LED** </span> blinks continuously: you have less than 15% of the battery (less than 4h of recording).
  - the <span style="color:green">**GREEN LED** </span>  blinks once, then becomes still: less than 50% of the battery.
  - the <span style="color:green">**GREEN LED** </span>  blinks twice, then becomes still: less than 75% of the battery.
  - the <span style="color:green">**GREEN LED** </span>  blinks 3x, then becomes still: more than 75% of the battery.

- The device is not ready for use if:
  - After powering on, none of the **2 LEDs** are **ON**. It means that the battery is critically low and needs to be charged.
  - During recording, the <span style="color:red">**RED LED** </span>  blinks 3 times and stops. It means that the battery is very low. You have to charge it.
  - After powering on, the <span style="color:green">**GREEN LED** </span>  is **ON** and turns **OFF** after a few seconds.  It means that there is a problem with the SD card (unplugged, corrupted or full). Check whether the SD card is present. If present, transfer the files to a computer and remove the files (see Step 4). If the problem is not solved, you will have to reformat the two partitions of the card. If the problem persists, try to change the SD card (see Appendix C. replace the SD card).

### <a name="Step2"></a>Step 2. How to record?

Press briefly on the "power" button. The BabyLogger is in recording mode if <span style="color:green">**the GREEN LED** </span> is stable; if the <span style="color:red">**RED LED** </span>  is blinking, it shows that the battery is low. Then, insert the BabyLogger in the breast pocket with the top of the cover facing up, and the three microphones in the front facing outside. To pause a recording, press slightly on the "power" button and to restart the recording, press again on the button.


### <a name="Step3"></a> Step 3. How to power off the logger?
Turn off the BabyLogger by pressing the power button (long press, 3 seconds). **All LEDs** should be **off**.



### <a name="Step4"></a> Step 4. How to transfer recordings?
- Remove the cover and click on the SD card (be careful: the SD card can jump out of the cover suddenly and it's tiny!).
- Insert the SD card into a MicroSD adaptor and plug it onto your computer (it should have been pre-configured for the logger [see this section](/getting-start/sd_card/).
- Drag and drop the files from both partitions (BL_MOTION and BL_AUDIO) to the 'Raw_Data' folder on the 'BabyLogger' repository.


##### <span style="color:RED">WARNING</span>
Be careful: you should decrypt the existing logger files on your computer before transferring any other new files from any logger; Not doing so will overwrite the still encrypted files on your computer.

### <a name="Step5"></a> Step 5. How to decrypt recordings?

To decrypt the files, follow the [decrypt process](/getting-start/decrypt/).
### <a name="Step6"></a> Step 6. How to recharge the logger?
- Remove the cover and plug your logger onto the micro USB charger. Any phone charger or computer USB port will do, but check that the voltage is not higher than 5V (for a normal charging time, the current capacity should be between 1A and 2A).

Figure 4. You can use a USB/ Micro-USB cable to charge your Logger with any standard charger (or your computer).



- When the BabyLogger is in charging mode: Both of the  <span style="color:green">**GREEN** </span> and  <span style="color:red">**RED** </span> **LEDs** are blinking.
- When the device is fully charged, the **two LEDs** stop blinking and the device turns itself off automatically.
- 2-3 hours are usually required to fully charge the logger.

##### <span style="color:RED">WARNING</span>
- It is impossible to record while the logger is being recharged.
- After the logger has been fully charged, it is impossible to charge the device again without using it before. This feature has been implemented for power saving purposes; the logger can be charged using an external battery without wasting energy when the battery is full. 

<b><i> We strongly recommend that you fully go through these 6 steps without skipping any (do not forget to fully transfer your data and recharge your device after each recording session in order to avoid losing data). </b></i>


