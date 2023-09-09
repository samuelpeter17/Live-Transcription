# Live-Transcription
Guide to creating live transcriptions for streams with OBS and Google Cloud

**First Time Directions**:
1. Go to the following link and download the closed_caption_plugin for your appropriate OS.
   https://github.com/ratwithacompiler/OBS-captions-plugin/releases
2. Extract the folder and copy **obs_google_caption_plugin.dll** from inside the subfolders.
   ![image](https://github.com/sam-vokamancy/Live-Transcription/assets/136375094/3683242c-3618-47af-87d7-61a189d08fa1)
3. Navigate to the location of installation for OBS/ obs-studio folder. For Windows: Navigate to C:\Program Files\obs-studio
4. Past the obs_google_caption_plugin.dll file into the obs-plugins folder
   ![image](https://github.com/sam-vokamancy/Live-Transcription/assets/136375094/7751ed1e-e3a0-498f-96da-b1e2cc8e3496)
5. Open the OBS app. If it is already open, close it and reopen the app.
6. In the menu bar, select **Docks** and make sure there is a check near Captions. If there isn't click on Captions.
7. This should now create a Captions box as seen in the image below.
   ![Screenshot 2023-08-09 110348](https://github.com/sam-vokamancy/Live-Transcription/assets/136375094/ffff82fa-3383-474a-8736-408d3f067bb7)
8. Click on the gear icon in the captions box.
   
   ![Screenshot 2023-08-09 110425](https://github.com/sam-vokamancy/Live-Transcription/assets/136375094/cd4515ac-bf7f-4300-a3ed-92e1f6425625)
10. In the dialogue box that appears make sure your settings of the General tab match the image below. Remember to click Save.
    ![image](https://github.com/sam-vokamancy/Live-Transcription/assets/136375094/fbfff39d-ecb6-41f7-8447-cfc8270e0ffc)
   Notes: You can change the language, number of lines and caption timeout depending on personal preferences.
11. Add a text source in the Sources dock and name it appropriately.
12. In the second dialogue box that appears, click on select font.
13. Choose your font style and set an appropriate font size. I would recommend 100.
14. Paste the following into the text section as seen below. This text will be updated later and is needed to adjust the location of where the transcription appears.

    ![image](https://github.com/sam-vokamancy/Live-Transcription/assets/136375094/a0f6a825-37fd-4905-926d-93ae0a4c4182)
15. Make any appropriate changes to edit the text color and click OK.
16. On the sample stream screen adjust the location of the text. If the text box is too big you can shrink it and adjust the font size accordingly.

    ![image](https://github.com/sam-vokamancy/Live-Transcription/assets/136375094/2a9ccf22-bd29-4791-b4eb-852000528db2)

17. Right-click on your text source in the sources tab. Select Transform and click on Edit Transform.

   ![image](https://github.com/sam-vokamancy/Live-Transcription/assets/136375094/98242509-4fd3-4aa0-bebc-6931ddec8a13)

19. Set the Positional Alignment to **Center** and Bounding Box Type to **Scale to inner bounds**.
    ![image](https://github.com/sam-vokamancy/Live-Transcription/assets/136375094/effe9882-9958-413e-903e-82e5c60d116d)
20. Click Close and readjust the text location to your desired location.
21. Right click on the gear icon of the captions tab(Step 8) and navigate to the Open Captions tab.
22. Click on Add Source and select your text source. Remember to Save your changes here.
    ![image](https://github.com/sam-vokamancy/Live-Transcription/assets/136375094/aacd3f30-bb92-48f1-a9dd-648aa17a3bf5)
23. You can now stream and the captions should update. If you want to test it, select the gear icon on the Captions Dock and click Show Preview from the Open Captions tab.

**Future Instructions**
Follow these if you have already set up live transcriptions once and got it to work.
1. Follow the above instructions from Step 6.


References:
https://www.youtube.com/watch?v=GsYDS4bKTpM

https://help.vidflex.com/article/284-obs-closed-captions-plugin
