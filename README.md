![Wii Shoplift Channel](http://transfer.archivete.am/9Qu6m/wiishop.png)

Before we begin, I will say that I'm not responsible for what you do with this, this tool is a grey area.

This tool is intended to provide a way to download games from the Wii Shop directly onto your Wii, even after shutdown.

After the disaster that was Rii Shop where I was hit with a accusation that I used it to dox people, which was false (and I got harassment and some scary stuff happened as a result and it devastated me how the community reacted), people have tried making a Wii Shop revival themselves, however I found that all of them have failed to make a working shop revival. None of them worked...until now.

How does this work? You install a patched IOS56 for the Wii Shop Channel, install a ton of tickets, and then use this homebrew app to select what game you want from the Wii Shop Channel, and it launches the shop then navigates to the download page in the Wii Shop Channel.

# Instructions

1.	Download **WiiXplorer** (if you are using a Wii) and the **Wii Shoplift Channel** application.
2.	Put the app and the **WAD** and **ticket** folder included in the zip file on your SD/USB. (If using a Wii U, you do not need to copy the ticket folder)
3.	Launch your favorite **WAD Manager** and install the patched **IOS56** for your corresponding system.
4.	If using a Wii, follow the instructions below for **Installing Tickets (WiiXplorer)** or **Installing Tickets (FTP)**. Otherwise, if you are using a Wii U, follow the instructions below for **Installing Tickets (Wii U Only)**. (WiiXplorer cannot install tickets properly on a Wii U)
5.	Open **Wii Shoplift Channel** and select the game you want to download. The **Wii Shop Channel** will download the game, and it will appear on your **Wii Menu**. Also, if you enable the option to download directly to the SD, it may not work if the file size is too large

## Installing Tickets (WiiXplorer)

1. Open **WiiXplorer**. Go to **Start** > **Settings** > **Boot Settings** > **Enable NAND Write Access**. Press **Yes**, then **Accept**, then press **Back** until you return to the main menu.
2.	Open the **ticket** folder on your SD/USB. Wait a couple of minutes. Hold down the **1 Button** on one of the files until all the files are highlighted, then select **Properties**. If the total file size is **1.69** MB, you can continue. Otherwise, you will have to wait for the other files to load.
3.	Hold down the **1 Button** on one of the files again, then press the **Plus Button**, then press Copy. Navigate to **NAND** > **ticket** > **00010001**.
4.	Press the **Plus Button** again, then press **Paste**. Wait until the process finishes. If you get a dialog asking if you want to replace files, select **No to All**.

## Installing Tickets (FTP)

1. Use **ftpii** or **ftpiiu** (on a Wii U) to start up a FTP server.
2. Use a FTP client on another device and enter the IP and port of the FTP server.
3. Copy the contents of the **ticket** folder included with **Wii Shoplift Channel** to your NAND folder -> **ticket** -> **00010001**. The NAND folder is called **isfs** if using **ftpii**, and **slccmpt01** if using **ftpiiu**. Wait a while for all the contents to be copied over.

# Wii Shop Error Codes

204036 - IOS isn't patched

204050 - Tickets not installed

205626 - Wii was region changed, either change your region to its prior setting or delete your Wii Shop account and try again

209601 - If you get this error you can ignore it
