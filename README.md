# Ungoogled-Updater
Just a simple bat script for launching ChrLauncher minimized on system boot to always update ungoogled-chromium. As well as the ini file.

Download entire repo and place in the 64 folder of ChrLauncher (or 32 if you want 32bit), and replace the ini file with the one provided (uses ungoogled chromium and doesnt actually launch the browser) 
You can edit the ini file to specify where you want it to install otherwise it'll install in the_current_dir\Ungoogled

Create a Task Scheduler task that calls the .bat file after user log ins, and delay for 30seconds
