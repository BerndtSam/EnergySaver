# EnergySaver
Want to save energy in your office space? Use this to ensure your office's desktops shut down at 6:30PM every night!

Currently works on Windows.


## Download
Download git https://git-scm.com/downloads
Open Git Bash
Navigate to an easily accessible directory
git clone https://github.com/BerndtSam/EnergySaver.git

## Enable
Open task scheduler

On the left navigation pane, select "Task Scheduler Library" -> Top Menu Bar -> Action -> Import Task -> Select "EnergySaverShutdown.xml" -> OK
Find the "EnergySaverShutdown" task in your list of tasks and ensure its Status is "Ready."

Your computer will now shut off at 6:30PM every night! 

## Disable
Open task scheduler

On the left navigation pane, select Task Scheduler Library -> Find "EnergySaverShutdown" -> Right click "EnergySaverShutdown" -> Disable.

## Extra Must Knows
If you're in the middle of something and you receive the shutting down notification, use the "Abort Shutdown" shortcut to abort the shutdown.

If you are about to turn off your computer you can use the "Nightly Shutoff" shortcut to turn your computer off in 10 minutes.

The shutdown time is modifiable by double clicking the imported "EnergySaverShutdown" task, selecting "Triggers" in the menu bar, selecting the "Daily" trigger, and under Settings modify the start time.

The countdown until shutdown is modifiable by double clicking the imported "EnergySaverShutdown" task, selecting "Actions," double clicking the Action "Start a program," and under "Add arguments (optional)," modify the 600 number to the duration in seconds you wish the timer to be.
