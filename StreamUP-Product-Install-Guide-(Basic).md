<h1 align="center">
    StreamUP Product Install Guide
</h1>

<h3 align="center">
    <a href="https://obsproject.com">
        <img alt="Supports OBS Studio version 28 and above" src="https://img.shields.io/badge/OBS Studio-28%2B-FFFFFF?style=for-the-badge&labelColor=1e1a1d">
    </a>
    <a href="https://streamer.bot">
        <img alt="Supports Streamer.Bot version 0.2.0 and above" src="https://img.shields.io/badge/Streamer.Bot-v0.2.0+-%23FFFFFF?style=for-the-badge&labelColor=9038e8">
    </a>
    <img alt="Supports Windows" src="https://img.shields.io/badge/Windows-%23FFFFFF?style=for-the-badge&logo=windows&labelColor=00a2ed">
</h3>

> <h4>Important</h4>
> If you are updating your StreamUP products from versions that were built for the old version of Streamer.Bot (before 0.2.0). You will need to remove the scenes in OBS and reinstall the new ones as a lot of changes have been made to improve performance etc.<br><br>
> This will mean you will lose any personal changes / customisation.<br><br>

<br>
<h1 align="center">
        OBS Setup
</h1>

1. Download & install the [StreamUP OBS plugin](https://ko-fi.com/s/0b5bd4536d)
    1. Extract the downloaded .zip file

    2. Copy the contents of the <kbd><b>Windows</b></kbd> folder into your <kbd><b>obs-studio</b></kbd> folder. The file path is usually: <kbd><b>C:\Program Files\obs-studio</b></kbd>

2. Open OBS then on the top menu bar, select <kbd><b>Tools -> StreamUP -> Check Product Requirements</b></kbd>. If you have any OBS plugins that need installing or updating they will be displayed here.<br>
<img src="Assets/General - Check Product Requirements.png" height="225" alt="Check product requirements ui screenshot">
<img src="Assets/General - Missing Or Outdated Plugin.png" height="225" alt="Missing or outdated plugin ui screenshot">

    1. You can then do one of the following:
         1. Download the [StreamUP Pluginstaller](https://streamup.tips/product/plugin-installer) and follow the [YouTube tutorial](https://youtu.be/6zMXZn4csI8)

         2. Click on each plugin. It will automatically use your web browser to download the selected plugin

    2. Install all the plugins downloaded into OBS by copying the files into the <kbd><b>obs-studio</b></kbd> folder just like you did for the StreamUP OBS plugin<br>
    <img src="Assets/General - OBS Plugin Folder.png" height="225" alt="OBS plugin install location screenshot">

<br>

<h1 align="center">
        Installing A Product Into OBS
</h1>

1. In OBS, on the top menu bar, select <kbd><b>Tools -> StreamUP -> Install a Product</b></kbd><br>
<img src="Assets/General - Install A Product Into OBS.png" height="225" alt="Install a product ui screenshot">

2. Navigate to the <kbd><b>2 - OBS INSTALL</b></kbd> folder and open the <kbd><b>.StreamUP</b></kbd> file. This will create a new scene/s in OBS<br>
<img src="Assets/General - Install StreamUP File.png" height="225" alt="Install .StreamUP file screenshot">

<br>

<h1 align="center">
        Installing A Product Into Streamer.Bot
</h1>

1. In Streamer.Bot, navigate to the tab <kbd><b>Servers/Clients → Websocket Server</b></kbd> and enable <kbd><b>Auto Start</b></kbd><br>
Configure the following settings then press <kbd><b>Start Server</b></kbd>
> Address - 127.0.0.1<br>
> Port - 8080<br>
> Endpoint - /<br><br>
<img src="Assets/General - SB Websocket Server Settings.png" height="225" alt="Install a product ui screenshot"><br><br>

2. Navigate to the tab <kbd><b>Stream Apps → OBS</b></kbd> and make sure your OBS is connected via websocket 5.x. Make a note of the connection number (by default this is <kbd><b>0</b></kbd>)<br>
<img src="Assets/General - SB OBS Connection Number.png" height="200" alt="OBS connection number ui screenshot">
<img src="Assets/General - SB OBS Connection.png" height="200" alt="OBS connection ui screenshot">

3. Press <kbd><b>Import</b></kbd> in the top left<br>
<img src="Assets/General - SB Import.png" height="225" alt="StreamerBot import ui screenshot">

4. Navigate to the <kbd><b>3 - BOT INSTALL\STREAMER.BOT</b></kbd> folder. Drag & drop the <kbd><b>.sb</b></kbd> into the <kbd><b>Import String</kbd></b> field. Press <kbd><b>Import</b></kbd><br>
<img src="Assets/General - SB File Import.png" height="200" alt=".SB file import screenshot">
<img src="Assets/General - SB Import Finish.png" height="200" alt=".SB file import screenshot">
> <h4>Important Note</h4>
> If you cannot drag and drop the file you can open it using <kbd><b>Notepad</b></kbd><br>
> Select all of the text <kbd>CTRL + A</kbd> and copy it <kbd>CTRL + C</kbd><br>
> Paste the copied text into the <kbd><b>Import String</b></kbd> box inside of Streamer.Bot<br><br>

5. Follow the product specific instructions to complete installation

