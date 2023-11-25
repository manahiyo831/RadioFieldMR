# RadioFieldMR 

日本語バージョンはこちら
https://github.com/manahiyo831/RadioFieldMR/blob/main/README_jp.md

## Overview
This app visualizes the strength of radio waves in space based on signals received with RTL-SDR. It is a version of RadioFieldAR, previously released for Android smartphones, now adapted for META QUEST. Thanks to QUEST's advanced tracking and QUEST3's color passthrough, measurements are more comfortable than ever. See it in action in these videos:

- [Video 1](https://youtu.be/FVZXz6tz3Ug)
<img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/bc41fb92-a089-426d-9376-7b5c74fdd1c7" width="50%">

- [Video 2](https://youtu.be/37uX_WTNvuA)
<img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/3e90962a-b3c6-468b-904b-41ca9eb701e2" width="50%">

**Note:**

- This is an experimental project, and I plan to make various improvements in the future. I also plan to support tinySA-ULTRA.

- Please use this app at your own risk.

- Currently, the number of measurement points is limited to a maximum of 500.

- Use within the Guardian area.

## Requirements
- **META QUEST2 or QUEST3:** Should work with QUEST-PRO, but not confirmed as I don't have the device. Not compatible with the original QUEST.
- **RTL-SDR:** Tested with V3.
 
  <img width="242" alt="image" src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/f9da3b71-660e-4558-944a-6a0cffb08a4e">

- **OTG Cable:** I use this one. Others might work, but please be aware that some may not function properly.
  [Purchase Link](https://www.amazon.co.jp/gp/product/B08LH1K2HF)
- **Antenna:** Prepare an antenna suitable for the frequency you wish to measure and connect it to the RTL-SDR.

## Installation
1. **RTL-SDR Driver:**
   Download the apk file and install it using SideQuest. If you're installing an apk for the first time, some settings are required. Please search the web for details.
3. **Checking RTL-SDR Functionality:**
    - Connect the RTL-SDR to the QUEST using the OTG cable.
      
      <img width="308" alt="image" src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/ef2f0a4f-458c-4d62-ba6e-1ad4c5ead330">

    - Run the RTL-SDR driver and select `ENABLE ADVANCED MODE`.
      
      <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/9c73530f-32d9-4b77-90b5-8ae971041601" width="50%">
      
      <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/82be10e4-4b94-44d1-9fa0-5de636976865" width="30%">
      
    - Select `START STREAM` and choose `OK` when prompted for permission.
      
      <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/63fb3356-a3c9-4821-978f-cb2a3d1be954" width="30%">
      
      <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/1e8d8df5-c7de-4e44-9b8e-123353537e8b" width="30%">
      
    - Ensure `[found 1 device opening options]` is displayed.
      
      <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/74f3f4d3-8bc1-43a6-8437-85d929526215" width="30%">
      
4. **APP Installation:**
   Download and install the apk file from release folder.
   https://github.com/manahiyo831/RadioFieldMR/releases

## How to Use
1. Launch the APP. This software is exclusively for hand tracking. Ensure hand tracking is functional and start the app without controllers.
  
   <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/7124186e-698e-41eb-be64-b627eef5eac6" width="50%">
3. Select `OK` when prompted for permission.
   
   <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/af8d3ad2-217c-4e52-a62c-f8a06394d646" width="50%">
4. If you return to the Quest menu screen, resume by palm pinching with your right hand.
5. Open your left hand to display the spectrum. A yellow star appears at the tip of your right index finger. A sphere representing radio wave strength will be drawn at this position. Pinch the star with your left hand to move it. Adjust the position to match the antenna.
   
   <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/d0b33801-6da8-4561-b4bf-fc4e4c974e4d" width="50%">
6. Frequency and other settings can be adjusted from the settings button.
   
   <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/f6f60832-6f2f-468f-942e-de44c303419a" width="50%">
7. Press the `REC` button on your right hand to start recording in space, turning the star red. Press again to stop recording.
    
    <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/5e6e5626-41b9-491d-bef6-4ce7d356b9ed" width="50%">

8. Move your right hand to move the star, drawing spheres at set grid intervals.    
   <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/adf450cd-6b54-49d4-8212-241d0d6a7ff1" width="50%">
   
9. Use the `Switch Shape` button to toggle between sphere and fog display.

    <img src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/5d0dfd68-ec02-4ea6-8b48-b8e607855cea" width="50%">
