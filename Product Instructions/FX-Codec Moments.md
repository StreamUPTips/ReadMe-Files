<h4 align="center">
  <img src="../Assets/Codec Moments FX - Banner.png" alt="Codec Moments">
</h4>

<h4 align="center">
  <a href="https://andistonemedia.mystl.ink">
    <img alt="A link to all of Andi's links" src="https://img.shields.io/badge/Created%20by%20Andi%20Stone%20(Andilippi)-white?style=for-the-badge">
  </a>
  <br><br>
    <a href="https://obsproject.com">
        <img alt="Supports OBS Studio version 28 and above" src="https://img.shields.io/badge/OBS Studio-28%2B-FFFFFF?style=for-the-badge&labelColor=1e1a1d">
    </a>
    <a href="https://streamer.bot">
        <img alt="Supports Streamer.Bot version 0.2.0 and above" src="https://img.shields.io/badge/Streamer.Bot-v0.2.0+-%23FFFFFF?style=for-the-badge&labelColor=9038e8">
    </a>
    <img alt="Supports Windows" src="https://img.shields.io/badge/Windows-%23FFFFFF?style=for-the-badge&logo=windows&labelColor=00a2ed">
  <br>
  <img alt="Supports Twitch" src="https://img.shields.io/badge/Supports Twitch-6441a5?style=for-the-badge&logo=twitch&logoColor=white">
  <img alt="Supports YouTube" src="https://img.shields.io/badge/Supports YouTube-red?style=for-the-badge&logo=youtube&logoColor=white"> 

</h4>

---

<br>

<h1 align="center">Initial Setup
</h1>

1. Complete the <kbd><b><a href="https://github.com/StreamUPTips/ReadMe-Files/blob/main/StreamUP-Product-Install-Guide.md">OBS & Streamer.Bot setup for StreamUP products</b></kbd><br></a>
*If you have already installed a StreamUP product with Streamer.Bot v0.2.0+ then you can skip this step*

<br>

<h1 align="center">
        OBS Setup
</h1>

1. Go to the scene you wish to start the Codec Call on. Add a new source and select <kbd><b>Scene</b></kbd><br>

    <img src="../Assets/Codec Moments FX - OBS Add Scene 1.png" alt="add scene screenshot"><br>

1. Select <kbd><b>Add Existing</b></kbd> and choose <kbd><b>StreamUP FX • Codec Moments</b></kbd> then press <kbd><b>OK</b></kbd> then lock the source<br>

    <img src="../Assets/Codec Moments FX - OBS Add Scene 2.png" alt="add scene part 2 screenshot"><br>

1. Go to the <kbd><b>StreamUP FX • Codec Moments (Edit Cams Here)</b></kbd> scene and add any cameras or sources you would like to use as the two callers. Resize and reposition them to your liking 

    <img src="../Assets/Codec Moments FX - Add Camera.png" alt="edit cameras screenshot"><br>

1. Go to the <kbd><b>StreamUP FX • Codec Moments</b></kbd> scene and right click the <kbd><b>Codec Moments • Waveform</b></kbd> source and select <kbd><b>Properties</b></kbd>

    <img src="../Assets/Codec Moments FX - Edit Waveform 1.png" alt="edit waveform 1 screenshot"><br>

1. Under the <kbd><b>Audio Source</b></kbd> option. Select the audio source you would like the waveform to animate to

    <img src="../Assets/Codec Moments FX - Edit Waveform 2.png" alt="edit waveform 2 screenshot"><br>

1. You may want to adjust the <kbd><b>Floor</b></kbd> and <kbd><b>Ceiling</b></kbd> options to adjust the sensitivity of the waveform to your audio source

    <img src="../Assets/Codec Moments FX - Edit Waveform 3.png" alt="edit waveform 3 screenshot"><br>

<br>

<h1 align="center">
        Streamer.Bot Setup
</h1>

1. Select the <kbd><b>Actions</b></kbd> tab. Under the <kbd><b>Actions</b></kbd> window on the left select <kbd><b>Codec Moments • Settings</b></kbd><br>
Under the <kbd><b>Triggers</b></kbd> window on the left, right click the top trigger and press <kbd><b>Test Trigger</b></kbd><br>

   <img src="../Assets/Codec Moments FX - Open Settings.png" alt="GameLad StreamerBot open settings page"><br>

1. Configure the products settings and follow any prompts on screen. Make sure the <kbd><b>OBS Connection Number</b></kbd> is set<br>
Press <kbd><b>Save</b></kbd> at the bottom of the window<br>

    <img src="../Assets/Codec Moments FX - Settings 1.png" alt="Codec Moments FX settings page 1">

1. To set up sound effects select the <kbd><b>Codec Moments • SFX • Codec Call Ringing</b></kbd> action. Double click the sub-action on the right and link it to a sound file on your pc then press <kbd><b>OK</b></kbd>. Repeat this process for each of the <kbd><b>SFX</b></kbd> Actions

    <img src="../Assets/Codec Moments FX - SFX 1.png" alt="Codec Moments FX add sound effects">

<h3>Example Effect</h3>

1. In the <kbd><b>Actions</b></kbd> tab. Under the <kbd><b>Actions</b></kbd> window on the left select <kbd><b>Codec Moments • Channel Point Example</b></kbd>. In the <kbd><b>Triggers</b></kbd> window in the top right, right click the trigger and press <kbd><b>Edit Trigger</b></kbd> then link it to a Twitch channel point. You can press <kbd><b>OK</b></kbd> 

    <img src="../Assets/Codec Moments FX - Edit Trigger.png" alt="Codec Moments FX edit example trigger in streamerbot">

1. Under the <kbd><b>Triggers</b></kbd> window right click the trigger again and press <kbd><b>Test Trigger</b></kbd>. You will then see it animate in OBS<br>

    <img src="../Assets/Codec Moments FX - Test Trigger.png" alt="Codec Moments FX edit example trigger in streamerbot">

1. You can see how this effect works but looking under the <kbd><b>Sub-Actions</b></kbd> window in the bottom right

    <img src="../Assets/Codec Moments FX - Example Action 1.png" alt="Codec Moments FX example">

<h3>Creating A Custom Effect</h3>

1. To create your own custom thing to happen during the codec call right click in the <kbd><b>Actions</b></kbd> window on the left and press <kbd><b>Add</b></kbd> 

    <img src="../Assets/Codec Moments FX - Custom Action 1.png" alt="Codec Moments FX add custom action 1">

1. Right click in the <kbd><b>Sub-Actions</b></kbd> window and select <kbd><b>Core -> Actions -> Run Action</b></kbd> 

    <img src="../Assets/Codec Moments FX - Custom Action 2.png" alt="Codec Moments FX add custom action 2">

1. Select the action <kbd><b>Codec Moments • Custom • 1. Codec Call Received</b></kbd> and press <kbd><b>Select</b></kbd>. Make sure you check the box that says <kbd><b>Run Action Immediately</b></kbd> then press <kbd><b>Ok</b></kbd> 

    <img src="../Assets/Codec Moments FX - Custom Action 3.png" alt="Codec Moments FX add custom action 3">

    <img src="../Assets/Codec Moments FX - Custom Action 4.png" alt="Codec Moments FX add custom action 4">

1. Repeat this process adding the other two actions <kbd><b>Codec Moments • Custom • 2. Start Codec Call</b></kbd> and <kbd><b>Codec Moments • Custom • 3. End Codec Call</b></kbd>. Make sure you have them in order and you can add whatever things you want to happen during the codec call inbetween action 2 and 3. Make sure you include delays etc, so the codec call doesn't end immediately. Some examples would be to include TTS using <kbd><b>Speaker.Bot</b></kbd> 

    <img src="../Assets/Codec Moments FX - Custom Action 5.png" alt="Codec Moments FX add custom action 5">

1. Right click in the <kbd><b>Triggers</b></kbd> window and create a new trigger for how you want this effect to work

    <img src="../Assets/Codec Moments FX - Custom Action 6.png" alt="Codec Moments FX add custom action 6">

1. You can then right click that trigger and press <kbd><b>Test Trigger</b></kbd>. You will then see the animation happen in OBS.

    <img src="../Assets/Codec Moments FX - Custom Action 7.png" alt="Codec Moments FX add custom action 7">

<br>

<br>

<h1 align="center">
        Frequently Asked Questions
</h1>

*For any further questions or support, join the [StreamUP Discord server](https://discord.com/invite/RnDKRaVCEu?)*

---

<br>

<h4 align="center">
  <img alt="Static Badge" src="https://img.shields.io/badge/A%20StreamUP%20Product-%23fc6caf?style=for-the-badge"><br>
  <a href="https://andistonemedia.mystl.ink">
    <img alt="A link to all of Andi's links" src="https://img.shields.io/badge/Created%20by%20Andi%20Stone%20(Andilippi)-white?style=for-the-badge">
  </a>  
</h4>
