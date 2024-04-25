### Recently Windows performed an update on my computer that has seemingly corrupted my .NET Framework installation. Every time I start up my computer and certain apps, I get notified that things can't be opened because I don't have NET version
### in this case I recommend that you try to install again those programs that are affected by this error;

## All process step by step given from here
### Run the Windows repair tools:

1. Press the Windows + X keys, select Command Prompt (Admin), copy and paste the commands below and press enter after each command.

2. sfc /scannow 

3. dism /online /cleanup-image /CheckHealth

4. dism /online /cleanup-image /restorehealth

5. chkdsk /f /r /b


Confirm with S and then Enter to schedule a disk scan. Restart the equipment and as soon as you finish, check if you agree.

### Wait for the process to finish and restart the pc;

Check the behavior;

I hope I helped, even more!
