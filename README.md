Mac DRAC Automation
----

**SECURITY NOTE:** *This workflow will open any and all files starting with viewer.jnlp with javaws when they land in your Downloads directory.  If you regularly work in environments where this could open you up to potential system compromise, don't use it on your default Downloads directory.*

----

DRAC 7 interfaces provide a horribly named JNLP file that is difficult to open without renaming the file or using `/usr/bin/javaws` on it directly.  This workflow will automatically open the JNLP file using javaws on your Mac.

### Getting started

1. Double-click the workflow file to install it into your *Folder Actions* directory.

2. Right click on the folder where your browser automatically downloads files (usually *Downloads*) and go to **Services > Folder Action Setup**.  Once the menu pops up, select **Open DRAC jnlp file.workflow** from the list.  Click **Attach**.

3. Close the Folder Actions Setup window and launch a virtual console from the DRAC 7 web interface.  You should see Java start up as soon as the file falls into the download folder.

----

*Disclaimer: Don't hold me responsible if this workflow causes your Mac to explode or chase cars.*
