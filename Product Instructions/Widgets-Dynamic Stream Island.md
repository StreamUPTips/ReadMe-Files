<h4 align="center">
  <img src="../Assets/Dynamic Stream-Island - Banner.png" alt="Dynamic Stream-Island">
</h4>

<h4 align="center">
  <a href="https://doras.to/andilippi">
    <img alt="A link to all of Andi's links" src="https://img.shields.io/badge/Created%20by%20Andi%20Stone%20(Andilippi)-white?style=for-the-badge">
  </a>
  <br><br>
    <a href="https://obsproject.com">
        <img alt="Supports OBS Studio version 28 and above" src="https://img.shields.io/badge/OBS Studio-28%2B-FFFFFF?style=for-the-badge&labelColor=1e1a1d">
    </a>
    <a href="https://streamer.bot">
        <img alt="Supports Streamer.Bot version 0.2.3 and above" src="https://img.shields.io/badge/Streamer.Bot-v0.2.3+-%23FFFFFF?style=for-the-badge&labelColor=9038e8">
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

2. Download & install the <kbd><b><a href="https://www.downloadfonts.io/san-francisco-font-free/">San Francisco Font</b></kbd></a>. You need to install all the fonts in the <kbd><b>SFUIText</kbd></a>, <kbd><b>SFUIDisplay</kbd></a> and <kbd><b>pro</kbd></a> folders <br>

<br>

<h1 align="center">OBS Setup
</h1>
<h3>Adding the Widget to Other Scenes</h3>

1. Go to the scene you wish to add the widget to. Add a new source and select <kbd><b>Scene</b></kbd><br>

    <img src="../Assets/Dynamic Stream-Island - OBS Add Scene 1.png" alt="add scene screenshot"><br>

1. Select <kbd><b>Add Existing</b></kbd> and choose <kbd><b>StreamUP Widgets • Dynamic Stream-Island</b></kbd> then press <kbd><b>OK</b></kbd><br>

    <img src="../Assets/Dynamic Stream-Island - OBS Add Scene 2.png" alt="add scene part 2 screenshot"><br>

1. Adjust the size and positioning of the alerts then lock the source<br>

    <img src="../Assets/Dynamic Stream-Island - Position In OBS.png" alt="positioning scene in obs screenshot">

<br>

<h1 align="center">
        Streamer.Bot Setup
</h1>

1. Select the <kbd><b>Actions</b></kbd> tab. Under the <kbd><b>Actions</b></kbd> window on the left select <kbd><b>DSI • Settings • Core</b></kbd><br>
Under the <kbd><b>Triggers</b></kbd> window on the right, right click the top trigger and press <kbd><b>Test Trigger</b></kbd><br>

   <img src="../Assets/Dynamic Stream-Island - Open Settings.png" alt="Dynamic Stream-Island StreamerBot open settings page"><br>

2. Configure the products settings and follow any prompts on screen. Make sure the <kbd><b>OBS Connection Number</b></kbd> is set<br>
When setting any local file paths you can just right click the file on your PC you want, then press <kbd><b>Copy as Path</b></kbd>. Paste that into the setting box.<br>
You will be able to set all kinds of settings such as choosing sound effects and each alert colour.
Press <kbd><b>Save</b></kbd> at the bottom of the window when happy<br>

    <img src="../Assets/Dynamic Stream-Island - Settings Page 1.png" alt="Dynamic Stream-Island settings page 1">

3. The next settings page will allow you to configure the settings for Twitch alerts. Press save when happy.<br>

    <img src="../Assets/Dynamic Stream-Island - Settings Page 2.png" alt="Dynamic Stream-Island - settings page 2"><br>

4. The next settings page will allow you to configure the settings for YouTube alerts. Press save when happy.<br>

    <img src="../Assets/Dynamic Stream-Island - Settings Page 3.png" alt="Dynamic Stream-Island - settings page 3"><br>

5. To test everything is working okay, head to the <kbd><b>Actions</b></kbd> tab and select <kbd><b>DSI • Alerts (Trigger)</b></kbd><br>
In the <kbd><b>Triggers</b></kbd> window on the right side, right click a trigger and press <kbd><b>Test</b></kbd>, check OBS to see the widget in action. It will animate the alert you tested.<br>

    <img src="../Assets/Dynamic Stream-Island - Test Main Action.png" alt="Dynamic Stream-Island test action in streamerbot"><br>

<br>

<h1 align="center">Finalising Setup
</h1>

To finish the setup you will need to enable some commands and features in Streamer.Bot that are disabled upon import.

1. Head to the <kbd><b>Commands</b></kbd> tab. Right click the <kbd><b>StreamUP Widgets • Dynamic Stream-Island</b></kbd> group, press <kbd><b>Group -> Enable All</b></kbd><br>

    <img src="../Assets/Dynamic Stream-Island - Finalise 1.png" alt="Dynamic Stream-Island - Enable Chat Commands"><br>

2. Head to the <kbd><b>Settings -> Timed Actions</b></kbd> tab. Right click <kbd><b>DSI • Rotator Timer</b></kbd>, press <kbd><b>Enabled</b></kbd><br> Please note: If you do not see the <kbd><b>DSI • Rotator Timer</b></kbd> then you can right click and press <kbd><b>Add</b></kbd> then create one manually. Set the timer to 20 seconds. You will then need to open the Rotator action and link that Timed Action to the trigger there.

    <img src="../Assets/Dynamic Stream-Island - Finalise 2.png" alt="Dynamic Stream-Island - Enable Timer Commands"><br>

<h1 align="center">
        Frequently Asked Questions
</h1>

<details>
  <summary><b>Q:</b> "I would like to stop a widget from appearing in the rotator"</summary>
  
  > You can disable any widgets you do not want to use by heading the <kbd><b>Actions</b></kbd> tab and on the left hand side, you can right click any of the <kbd><b>(Trigger)</b></kbd> or <kbd><b>(Widget)</b></kbd> actions and press <kbd><b>Enabled</b></kbd><br>
      <img src="../Assets/Dynamic Stream-Island - Disable Action.png" alt="Dynamic Stream-Island - Enable Timer Commands"><br>

</details>

*For any further questions or support, join the [StreamUP Discord server](https://discord.com/invite/RnDKRaVCEu?)*

---

<br>

<h4 align="center">
  <img alt="Static Badge" src="https://img.shields.io/badge/A%20StreamUP%20Product-%23fc6caf?style=for-the-badge"><br>
  <a href="https://doras.to/andilippi">
    <img alt="A link to all of Andi's links" src="https://img.shields.io/badge/Created%20by%20Andi%20Stone%20(Andilippi)-white?style=for-the-badge">
  </a>  
</h4>
