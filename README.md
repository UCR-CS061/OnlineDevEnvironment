# CS061 - Programming Assignment 1

## Running LC3Tools in a GitHub Codespace

This GitHub repository has all the configuration necessary to run as a Codespace on GitHub. Any free GitHub user can start a codespace and run this simulation entirely in a browser. Free GitHub accounts come with upto 120 hours of free Codespace usage per month.

To start the codespace, on this GitHub page click on Code -> Codespaces -> "Create Codespace on main". This action will start the set up of the codespace. This process can take anywhere from 5 to 10 minutes.

Once it is complete, you will be in Visual Studio Code in your browser. To run Digital, you will need to open a VNC tab. At bottom of the Visual Studio Code window you may see several tabs including Problems, Output, Terminal, and Ports. If you do not see these tabs go to View -> New Terminal, and you should see the tabs. Click on the Ports tab. Find the port 6080 and hover over it in the column "Local Address". You should then see a globe icon. Click on this icon, which will launch a new tab in your browser. This opens the NoVNC tab, press the "Connect" button and you are then asked for a password. The password is "cs061". Enter this password and press "Send credentials". You should now see a windows session that looks like the following:

At the lower left of this window you will see an arrow and the time. If you don't see it, scroll down until you do. Click on the arro and select Digital. This will open the logic design program, Digital. In this program, click File -> Open. In the file dialog box navigate to th directory /LC3_realized and select lc3.dig and then press "Open". You are now in the LC3 simulator. See the section below called "Running the Simulator"
Some useful settings for NoVNC

The NoVNC web app has some annoying behaviors. Two of these behaviors is poor window sizing and constant disconnections. To lessen the impact of thse behvaviors, you can set a couple of setting. In the middle of the screen on the left hand side of the NoVNC tab there is a blue arrow pointing to the right. Click on this arrow and then the settings gear. On the dialog that opens, select "Remote Resizing" under "Scaling Mode" and put a check mark next to "Automatic Reconnect" under "Advanced". The settings should look like the following when you're done:

Once your done, select the blue arrow now pointing to the left to close the settings dialog. These setting should make the behaviors a little less annoying.
