# Dodi-Repacks-Crash-Fix
A simple but detailed guide which focusses on crashfixes for games download through dodi repacks
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FKillshot1337x%2FDodi-Repacks-Crash-Fix&count_bg=%236DC828&title_bg=%23D30000&icon=checkmarx.svg&icon_color=%232D0303&title=Today%27s%2FTotal+Viewers&edge_flat=false)](https://hits.seeyoufarm.com)


### This guide is for people who are facing crash issues with games downloaded from dodi repacks.We'll be focussing on the common causes for these crashes in this guide.A star to the repo would be appreciated.

Before we begin, you should know how to run event viewer to diagnose errors. [Here's a quick guide for it](https://pastebin.com/VxM1ZKW5)

**Case #1: Game not launching at all** 

Fix 1-
        This is a fix if your crack has been damaged by your anti virus.Always keep all your Anti Viruses disabled when 
        dealing with repacks. 
        
        To see if your anti virus is causing the error, run event viewer. If you see an error which specifies the faulting module as a
        dll or exe file present in the game directory, this fix is for you. After turning your anti virus off, go to your torrent client and force recheck the torrent.
        Here's a simple guide for it: https://telegra.ph/Rehash-Force-Recheck-files-in-torrent-clients-03-02
        Then re install the game and see if it works.Alternatively, you can get cracks from cs.rin.ru, but force rechecking is easier.

Fix 2-
       

        Run event viewer using the guide given at the start of the guide.If you notice an error which says that something like Faulting module 
        name: ntdll.dll is causing the error,it is a windows build error. In this case, you'll have to either switch to windows 10, or windows 11
        build 22478. 
**SOME CRACKS DO NOT WORK AS INTENDED ON ALL BUILDS OF WIN 11**

        There are many guides on youtube and google, which will guide you on how to switch to that specific build/windows.
        I'm mentioning 2 of them here: 
        Guide to downgrade to win 11 build 22478- https://technclub.com/guides/download-windows-11-22478/

        Guide to switch to win 10- https://www.youtube.com/watch?v=OtHZueEZe9s
        PS: You can use programs like KMS to activate win10/11 for free

Fix 3-

        In the event viewer,if you get an error which says that the faulting module is C:/Windows/System32/vrfcore.dll,
        like https://imgur.com/f7d8cpL, it is a windows registry issue.Vrfcore.dll is used by Application Verifier and 
        it creates registry entries in some cases. Make sure you don't  delete or change anything else while trying to 
        fix it.Follow these steps for the fix:
        Goto Registry editor(win+R->regedit)then go to HKEY_LOCAL_MACHINE->SOFTWARE->Microsoft->Windows NT->CurrentVersion->
        Image File Execution Options -> (Your application name.exe). 
        Then right Click and export the registry settings for backup. (IMPORTANT)
        ->Then delete the registry entry for your application and try to run the game.
        This should fix the problem and the game should work fine.
        
**Case #2- 
        The game launched earlier but it's not launching now/the game is crashing at specific points only**

Fix-
        
        This is a very generic problem.More information is required to work on a fix for it.Your best bet is to scout google and reddit
        threads for users facing the same problem.If you still can't figure it out, come to dodi's server(#help-section), the invite is given below.
        You can also create an issue on this repository.
        
[Dodi's server invite](https://discord.gg/tBFvqdQjZe)

#### Thank you for reading this guide,hope it helps.You can contribute to it by joining dodi's server and helping people there or opening a PR for this repo.Don't forget to give a star if you enjoyed it :)   
Peace out,
Killshot.
      
