# Roku-Stream-Alarm

This project is built directly off code from rokudev: https://github.com/rokudev/samples

You must enable developer mode on roku in oder to install this app and send remote commands to the roku: https://blog.roku.com/developer/developer-setup-guide

**Step 1 (RokuAlarm/components/videoscene.xml)**

Change {StreamURL} to proper http url you would like to veiw.

**Step 2 (RokuPost.ps1)**

Change {ROKU_IP_ADDRESS} to the proper Roku Device IP address (Consider setting static IP Address)

**Step 3**

Zip and Sideload app to roku device: https://developer.roku.com/docs/developer-program/getting-started/developer-setup.md

**Step 4**

Setup task scheduler or crontab to run powershell script or curl request to roku device at whatever times and data you want.
