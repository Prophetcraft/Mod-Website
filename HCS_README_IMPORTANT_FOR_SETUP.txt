HCS - Hytale Control Suite README

Hey! Don’t worry about all the folders you see. They are required for
the controller to work properly. You do NOT need to modify those files
manually.

Just follow this guide. The setup wizard will help you configure
everything step by step.

------------------------------------------------------------------------

WHAT IS HCS?

HCS (Hytale Control Suite) is a controller that lets you manage your
Hytale server from: - A Web Dashboard - Discord

You can: - Start / Stop / Restart the server - Monitor RAM and CPU -
Upload and manage mods - Receive Discord notifications - Schedule system
shutdown - View logs and activity

------------------------------------------------------------------------

REQUIREMENTS

Before starting, make sure you have:

-   Windows
-   Node.js installed
-   A Hytale server already installed
-   A Discord bot token
-   A Discord channel ID

------------------------------------------------------------------------

All the scripts that you need are in Controller.v1.1/scripts.
Or you can also create a shortcut of the scripts that you need.

------------------------------------------------------------------------

STEP-BY-STEP INSTALLATION

STEP 1 - INSTALL Run this file: install.bat

This will install everything needed to run HCS.

------------------------------------------------------------------------

STEP 2 - CONFIGURE Run: configure.bat

The wizard will ask you for: - Discord bot token - Discord channel ID -
Hytale server folder - Hytale config.json path - Server start file -
Dashboard URL (localhost, LAN IP or DDNS)

At the end, the wizard will create the configuration file automatically.

------------------------------------------------------------------------

STEP 3 - START CONTROLLER Run: start.bat

The controller will start and show you: - Controller status - Log
window - Dashboard URL

Open the dashboard URL in your browser.

Also you can close all the CMDs windows after the controller is online cause the process of node.js runs in background.

------------------------------------------------------------------------

STEP 4 - If you need to STOP the CONTROLLER Run: stop.bat

The controller will stop.

------------------------------------------------------------------------

USEFUL COMMANDS

Start controller: scripts.bat

Stop controller: scripts.bat

Restart controller: scripts.bat

Re-run configuration: scripts.bat

------------------------------------------------------------------------

DASHBOARD ACCESS

You can use the dashboard in different ways:

Local only: http://127.0.0.1:3000

Local network: http://YOUR_LOCAL_IP:3000

Public (DDNS): http://your-ddns:3000

------------------------------------------------------------------------

LOG FILE

Logs are stored here: runtime.log

The log file is cleared every time the controller starts.

------------------------------------------------------------------------

IMPORTANT NOTES

-   Do NOT delete the project folders.
-   Do NOT modify core files unless you know what you are doing.
-   Always use the scripts inside the “scripts” folder.
-   The dashboard does NOT open automatically when the controller
    starts.
-   The controller must be running for Discord and the dashboard to
    work.

------------------------------------------------------------------------

QUICK SUMMARY

1.  scripts.bat
2.  scripts.bat
3.  scripts.bat
4.  Open dashboard in browser

------------------------------------------------------------------------

HCS - Hytale Control Suite
