Mac DRAC Automation
----

DRAC 7 interfaces provide a horribly named JNLP file that is difficult to open without renaming the file or using `/usr/bin/javaws` on it directly.  This workflow will automatically open the JNLP file using javaws on your Mac.

To set it up, move the workflow file from the repository into the folder actions folder in your home directory:

    my "Open DRAC jnlp file.workflow" "~/Library/Workflows/Applications/Folder Actions/"

Open a Finder window within your home directory:

    open ~/

Right click on the folder where your browser automatically downloads files (usually *Downloads*) and go to **Services > Folder Action Setup**.  Once the menu pops up, select **Open DRAC jnlp file.workflow** from the list.  Click **Attach**.

Close the Folder Actions Setup window and launch a virtual console from the DRAC 7 web interface.  You should see Java start up as soon as the file falls into the download folder.