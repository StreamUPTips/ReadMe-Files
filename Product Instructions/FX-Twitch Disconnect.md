<h4 align="center">
  <img src="../Assets/Twitch Disconnect FX - Banner.png" alt="Twitch Disconnect">
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

</h4>

---

<br>

<h1 align="center">Initial Setup
</h1>

1. Complete the <kbd><b><a href="https://github.com/StreamUPTips/ReadMe-Files/blob/main/StreamUP-Product-Install-Guide.md">OBS & Streamer.Bot setup for StreamUP products</b></kbd><br></a>
*If you have already installed a StreamUP product with Streamer.Bot v0.2.0+ then you can skip this step*

<br>

<h1 align="center">
        Streamer.Bot Setup
</h1>

1. Select the <kbd><b>Actions</b></kbd> tab. Under the <kbd><b>Actions</b></kbd> window on the left select <kbd><b>Twitch Disconnect • Settings</b></kbd><br>
Under the <kbd><b>Triggers</b></kbd> window on the right, right click the top trigger and press <kbd><b>Test Trigger</b></kbd><br>

   <img src="../Assets/Twitch Disconnect FX - Open Settings.png" alt="Twitch Disconnect StreamerBot open settings page"><br>

2. Configure the products settings and follow any prompts on screen. Make sure the <kbd><b>OBS Connection Number</b></kbd> is set<br>
Press <kbd><b>Save</b></kbd> at the bottom of the window<br>

    <img src="../Assets/Twitch Disconnect FX - Settings 1.png" alt="Twitch Disconnect FX settings page 1">

3. You need to set how you want this effect to trigger by selecting the <kbd><b>Actions</b></kbd> tab. Under the <kbd><b>Actions</b></kbd> window on the left select <kbd><b>Twitch Disconnect • Main Action</b></kbd><br>
Under the <kbd><b>Triggers</b></kbd> window on the right, right click and create a trigger. This is completely up to you how you cant to trigger this effect

    <img src="../Assets/Twitch Disconnect FX - Create Trigger.png" alt="Twitch Disconnect FX create trigger">

<br>

<h1 align="center">
        Non-Full Screen Mode
</h1>

If you are using this effect with <kbd><b>Full Screen Mode</b></kbd> disabled, you will need to do some extra steps.

1. In the product settings you can disable <kbd><b>Full Screen Mode</b></kbd> then press <kbd><b>Save</b></kbd>. This will open a message and prompt you to select a source in OBS that you want this effect to work on. Then press <kbd><b>OK</b></kbd>

    <img src="../Assets/Twitch Disconnect FX - OBS Select Source.png" alt="Twitch Disconnect FX create trigger">

2. Go to the <kbd><b>StreamUP FX • Twitch Disconnect</b></kbd> scene and turn the visibility on for the <kbd><b>Twitch Disconnect • Connection Lost</b></kbd> source

    <img src="../Assets/Twitch Disconnect FX - OBS Toggle Visibility.png" alt="Twitch Disconnect FX create trigger">

3. You then need to add the <kbd><b>StreamUP FX • Twitch Disconnect</b></kbd> to another scene. Go to the scene you wish to add the effect to. Add a new source and select <kbd><b>Scene</b></kbd><br>

    <img src="../Assets/Twitch Disconnect FX - OBS Add Scene 1.png" alt="add scene screenshot"><br>

4. Select <kbd><b>Add Existing</b></kbd> and choose <kbd><b>StreamUP FX • Twitch Disconnect</b></kbd> then press <kbd><b>OK</b></kbd><br>

    <img src="../Assets/Twitch Disconnect FX - OBS Add Scene 2.png" alt="add scene part 2 screenshot"><br>

5. Adjust the size and positioning of the effect then lock the source<br>

    <img src="../Assets/Twitch Disconnect FX - Position In OBS.png" alt="positioning scene in obs screenshot">

6. You can then test the trigger you set in the previous steps to make sure it all works correctly.

<br>

<h1 align="center">
        Muting / Unmuting Sources
</h1>

To make the effect look a lot better you can mute and unmute audio sources to make it look like you have actually disconnected. To do this, do the following:

1. In Streamer.Bot select the <kbd><b>Actions</b></kbd> tab. Under the <kbd><b>Actions</b></kbd> window on the left select <kbd><b>Twitch Disconnect • Mute Sources (User Input Required)</b></kbd><br>
Under the <kbd><b>Sub-Actions</b></kbd> window on the right, double click the <kbd><b>OBS Source Mute State</b></kbd> action then set it to a source you want to mute

    <img src="../Assets/Twitch Disconnect FX - Mute 1.png" alt="muting a source in streamer.bot">
    <img src="../Assets/Twitch Disconnect FX - Mute 2.png" alt="muting a source in streamer.bot">

    You can then duplicate this Sub-Action as many times as you need for different sources by right clicking it and pressing <kbd><b>Duplicate Sub-Action</b></kbd>

    <img src="../Assets/Twitch Disconnect FX - Mute 5.png" alt="unmuting a source in streamer.bot">

2. Select the <kbd><b>Actions</b></kbd> tab. Under the <kbd><b>Actions</b></kbd> window on the left select <kbd><b>Twitch Disconnect • Unmute Sources (User Input Required)</b></kbd><br>
Under the <kbd><b>Sub-Actions</b></kbd> window on the right, double click the <kbd><b>OBS Source Mute State</b></kbd> action then set it to a source you want to unmute

    <img src="../Assets/Twitch Disconnect FX - Mute 3.png" alt="unmuting a source in streamer.bot">
    <img src="../Assets/Twitch Disconnect FX - Mute 4.png" alt="unmuting a source in streamer.bot">

    You can then duplicate this Sub-Action as many times as you need for different sources by right clicking it and pressing <kbd><b>Duplicate Sub-Action</b></kbd>

    <img src="../Assets/Twitch Disconnect FX - Mute 6.png" alt="unmuting a source in streamer.bot">

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
