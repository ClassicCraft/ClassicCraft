# ClassicCraft Server
This is a modified version of the Minecraft Classic Server that has been fixed, after being broken for years.
# How to Compile
Note: The server only works on Windows at this point in time. Mac version coming soon.
1. First, you must obtain an official server zip from here: http://s3.amazonaws.com/MinecraftDownload/minecraft_classic_server.zip
2. Download 7-Zip from http://www.7-zip.org/download.html
3. Follow the installer to install 7-Zip.
4. Once 7-Zip is installed, extract the server zip using it (if you don't know how, google it, noob).
5. Open the new minecraft_classic_server folder in your file explorer
6. Right click the minecraft-server.jar file, hover over 7-Zip, then click Open Archive.
7. Go to http://rawgit.com/ClassicCraft/ClassicCraft/master/server/com/mojang/minecraft/server/d.class to download the required file.
8. In 7-Zip, click the com folder, then click mojang, then click minecraft, then click server.
9. Open a file explorer, then go to the directory where you downloaded d.class.
10. Drag d.class from your file explorer to the 7-Zip window.
11. Click Yes in the pop-up window.
12. Close 7-Zip.
13. You're all set! To run the server, click "start server.bat" without the quotes to start your new server.
14. Well, we kinda lied when we said you're all set. One more thing. Once you start the server for the first time, close it.
15. Then, there should be a new file in your minecraft_classic_server folder, server.properties.
16. Open it with Notepad (again, google if you don't know how).
17. Change verify-names from true to false (otherwise it will not let players join; we're working on a fix).
17-1. Note: Even though the server says players can impersonate other players when this is false, that is no longer true.
18. Okay, you're good to go! Now just click "start server.bat" to run the server!
