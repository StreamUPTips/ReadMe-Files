# CARDS AGAINST HUMANITY¹

### Features
- Easy installation
- Interactive channel point
- Fully animated in OBS
- TONS OF FUN, OFFENSIVE¹ AND AWKARDNESS

### Prerequisites
- [OBS Studio 28+](https://obsproject.com/)
- [StreamUP Recommended Plugins](https://streamup.tips/product/plugin-installer)
- [Streamer.bot](https://streamer.bot)
- [Inter font family](https://rsms.me/inter/)

## Installation Instructions
Please, make sure you have all the prerequisites installed before performing the product installation itself.  
Be sure to have OBS closed when installing these plugins.

## Streamer.bot instructions

1. Unpack the downloaded zip file to a folder of your choosing. There should be a folder created called 'StreamUP - Cards Against Humanity'. Be sure not to move it after installing this product!
2. Open OBS Studio, press 'Tools' from the top menu bar. Press 'StreamUP'.
3. Navigate to the 'StreamUP - Cards Against Humanity' folder you extracted earlier and select the '.StreamUP' file. This will create a new OBS scene.
4. Open Streamer.Bot, Click the 'Import' button on top
5. Drag and drop the 'Streamer.Bot Install' sb file into the top 'Import String' box, or copy and paste the contents of the sb file into that window. Then press 'Import' in the bottom right. 

You now can do a couple of things, make a singular automatic reward which the cards automatically popup and / or make seperate rewards for the black and white cards. 
With the seperate rewards you can make chat fill in the white card. But be aware chat can be more offensive than the actual game!²
  
#### Automatic cards

1. In the triggers windows, double click on 'Twitch > Channel Reward'
2. Create or Select your Cards against Humanity Reward

If you going to create your rewards make sure you set the correct settings:
(You can click on 'Create Reward' in the Selection Window)

1. Fill in all the channel point information on this page that popped out.
2. Set the Global Cooldown to **atleast** 20 seconds or more.
   
That's it! The automatic way is now set up and ready to use!

#### Separate Cards

1. On the 'StreamUP Widgets - Cards Against Humanity - Black Redeem' &  'StreamUP Widgets - Cards Against Humanity - White Redeem' action trigger window, double click on 'Twitch > Channel Reward'
2. Create or Select your Black and / or White Cards against Humanity Reward Redeem
   
If you going to create your rewards make sure you set the correct settings:
(You can click on 'Create Reward' in the Selection Window)

Black Card Settings:  
+ Fill in all the channel point information on this page that popped out for the black card.

White Card Settings:  
+ Fill in all the channel point information on this page that popped out for the white card, _make sure to press the checkbox 'User Input Required'_.

Black Card Sub-Actions:
1. You should see 2 'Reward Set Enabled State' subactions with unknown it. Double click the top one and select your newly created reward for the black card and press Ok
2. On the bottom 'Reward Set Enabled State' you set the reward you created for the White Card and press Ok.

White Card Sub-Actions:
1. On the top 'Reward Set Enabled State' select your White Card Reward and press Ok.
2. On the bottom 'Reward Set Enabled State' select your Black Card Reward and press Ok.

That's it! The separate way is now set up and ready to use!

If it is not working when you test the Channel Point, it is most likely that you do not have one of the Prerequisites installed.

¹This widget can be quite offensive just like the real Cards Against Humanity. If you or your chat is easily offended please don't use widget!

²StreamUP is not responsible for your chat and can not be hold accountable for anything that your chat puts in the white card!
