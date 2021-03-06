# CARDS AGAINST HUMANITY¹

### Features
- Easy installation
- Interactive channel point
- Fully animated in OBS
- TONS OF FUN, OFFENSIVE¹ AND AWKARDNESS

### Prerequisites
- [OBS Studio](https://obsproject.com/)
- [OBS Websocket - OBS Plugin](https://obsproject.com/forum/resources/obs-websocket-remote-control-obs-studio-from-websockets.466/)
- [StreamUP - OBS Plugin](/plugin)
- [Move Transition - OBS Plugin](https://obsproject.com/forum/resources/move-transition.913/)
- [ShaderFilter - OBS Plugin](https://obsproject.com/forum/resources/obs-shaderfilter.775/)
- [Streamer.bot](https://streamer.bot)
- [Inter font family](https://rsms.me/inter/)

### Installation Instructions
Please, make sure you have all the prerequisites installed before performing the product installation itself.
Be sure to have OBS closed when installing these plugins.
If you need help installing any of these google: "`Andilippi plugin name`" there will be a video to help you.

### Streamer.bot instructions

1. Unpack the downloaded zip file to a folder of your choosing. There should be a folder created called 'StreamUP - Cards Against Humanity'. Be sure not to move it after installing this product!
2. Open OBS Studio, press 'Tools' from the top menu bar. Press 'StreamUP'.
3. Navigate to the 'StreamUP - Cards Against Humanity' folder you extracted earlier and select the '.StreamUP' file. This will create a new OBS scene.
4. Open Streamer.Bot, go to the 'Actions' tab at the top. Right click anywhere in the 'Actions' box on the left. Press 'Import'.
5. Drag and drop the 'Streamer.Bot Install' text file into the top 'Import String' box. Then press 'Import' in the bottom right. 

You now can do a couple of things, make a singular automatic reward which the cards automatically popup and / or make seperate rewards for the black and white cards. 
With the seperate rewards you can make chat fill in the white card. But be aware chat can be more offensive than the actual game!²
  
#### Automatic cards

1. Got to the 'Channel Point Rewards' tab at the top. Right click in the box below and press 'Add'.
2. Fill in all the channel point information on this page that popped out.
3. Set the Global Cooldown to atleast 20 seconds or more.
4. At the bottom under 'Other Settings'. Press the dropdown menu next to 'Action' and select 'StreamUP Widgets - Cards Against Humanity - Automatic'.
5. That's it! The automatic way is now set up and ready to use!

#### Separate Cards

1. Got to the 'Channel Point Rewards' tab at the top. Right click in the box below and press 'Add'.
2. Fill in all the channel point information on this page that popped out for the black card.
3. At the bottom under 'Other Settings'. Press the dropdown menu next to 'Action' and select 'StreamUP Widgets - Cards Against Humanity - Black Redeem' and press Ok.
4. On the same page add another reward
5. Fill in all the channel point information on this page that popped out for the white card, make sure to press the checkbox 'User Input Required'.
6. At the bottom under 'Other Settings'. Press the dropdown menu next to 'Action' and select 'StreamUP Widgets - Cards Against Humanity - White Redeem' and press Ok.
7. Go to the 'Actions' tab at the top. Click on 'StreamUP Widgets - Cards Against Humanity - Black Redeem'
8. You should see 2 'Reward Set Enabled State' subactions with unknown it. Double click the top one and select your newly created reward for the black card and press Ok
9. On the bottom 'Reward Set Enabled State' you set the reward you created for the White Card and press Ok.
10. On the same tab go to 'StreamUP Widgets - Cards Against Humanity - White Redeem'.
11. On the top 'Reward Set Enabled State' select your White Reward and press Ok.
12. On the bottom 'Reward Set Enabled State' select your Black Reward and press Ok.
13. That's it! The separate way is now set up and ready to use!

If it is not working when you test the Channel Point, it is most likely that you do not have one of the Prerequisites installed.

¹This widget can be quite offensive just like the real Cards Against Humanity. If you or your chat is easily offended please don't use widget!

²StreamUP is not responsible for your chat and can not be hold accountable for anything that your chat puts in the white card!
