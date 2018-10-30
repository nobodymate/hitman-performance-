# Hitman6 Performance++

@echo off
title H6 Performance++ v.0.01 by antarlz

@echo [32mThis is basically a simple launcher waiting Hitman 6 to be manually started.
@echo Many optimizations/workarounds are gonna be executed while the game is running and restaure the original state when not.
@echo Hitman 6 is gonna have a higher priority while some useless win10 bacckground processes are gonna have
@echo themselves lowered/closed constantly. Feel free to suggest other useless garbage your pc might run at thi1337@hotmail.com
@echo I will release a 'soft' version that doesn't close explorer.exe eventually aswell.[0m
@echo [35mFuck you Ian :)[0m
@echo [32m...[0m

:Launch
@echo [33myou still have to open the game
tasklist /FI "IMAGENAME eq HITMAN.exe" | findstr "HITMAN.exe" >nul
if %ERRORLEVEL% == 0 goto Detected [0m
timeout 5
@echo [31mWaiting for you to launch Hitman 6...
goto Launch

:Detected
cls
@echo [0mFound HITMAN.exe! Giving 1(one) minute until the game is fully launched then optimizations are gonna start.
timeout 60
@echo off
[32m powercfg -s 8c5e7fda-e8bf-4a96-9a85-a6e23a8c635c
wmic process where name="HITMAN.exe" CALL setpriority "128"
wmic process where name="Gameoverlayui.exe" CALL setpriority "64"
wmic process where name="subprocess.exe" CALL setpriority "64"
wmic process where name="SearchUI.exe" CALL setpriority "64"
wmic process where name="Battle.net.exe" CALL setpriority "64"
wmic process where name="ShellExperienceHost.exe" CALL setpriority "64" 
wmic process where name="dwm.exe" CALL setpriority "64"
wmic process where name="audiodg.exe" CALL setpriority "64"
wmic process where name="Skype.exe" CALL setpriority "64"
wmic process where name="Firefox.exe" CALL setpriority "64"
wmic process where name="Photoshop.exe" CALL setpriority "64"
wmic process where name="Cmd.exe" CALL setpriority "64"
wmic process where name="Chrome.exe" CALL setpriority "64"
wmic process where name="Steam.exe" CALL setpriority "64"
wmic process where name="services.exe" CALL setpriority "64"
wmic process where name="SecurityHealthService.exe" CALL setpriority "64"
wmic process where name="SecHealthUI.exe" CALL setpriority "64"
wmic process where name="Opera.exe" CALL setpriority "64"
wmic process where name="SearchUI.exe" CALL setpriority "64"
wmic process where name="ShellExperienceHost.exe" CALL setpriority "64" 
wmic process where name="smartscreen.exe" CALL setpriority "64"
wmic process where name="dwm.exe" CALL setpriority "64"
wmic process where name="MsMpEng.exe" CALL setpriority "64"
wmic process where name="subprocess.exe" CALL setpriority "64"
wmic process where name="wordpad.exe" CALL setpriority "64"
wmic process where name="Steamwebhelper.exe" CALL setpriority "64"
wmic process where name="ts3client_win64.exe" CALL setpriority "64"
wmic process where name="SteamService.exe" CALL setpriority "64"
wmic process where name="steamwebhelper.exe" CALL setpriority "64"
wmic process where name="GameOverlayUI.exe" CALL setpriority "64"
wmic process where name="MicrosoftEdge.exe" CALL setpriority "64"
wmic process where name="MicrosoftEdgeCP.exe" CALL setpriority "64"
wmic process where name="explorer.exe" CALL setpriority "64"
wmic process where name="explorer.exe" CALL setpriority "64"
wmic process where name="RadeonSettings.exe" CALL setpriority "64"
wmic process where name="Spotifycrashservice.exe" CALL setpriority "64"
wmic process where name="Spotifywebhelper.exe" CALL setpriority "64"
wmic process where name="upc.exe" CALL setpriority "64"
wmic process where name="UplayWebCore.exe" CALL setpriority "64"
wmic process where name="AsusAudioCenter.exe" CALL setpriority "64"
wmic process where name="Spotify.exe" CALL setpriority "64"
wmic process where name="Isass.exe" CALL setpriority "64"
wmic process where name="NisSrv.exe" CALL setpriority "64"
wmic process where name="explorer.exe" CALL setpriority "64"
wmic process where name="explorer.exe" CALL setpriority "64"
wmic process where name="Origin.exe" CALL setpriority "64"
wmic process where name="CCleaner64.exe" CALL setpriority "64"
wmic process where name="Uplay.exe" CALL setpriority "64"
wmic process where name="Sidebar.exe" CALL setpriority "64"
wmic process where name="Dvm.exe" CALL setpriority "64"
wmic process where name="Discord.exe" CALL setpriority "64"
wmic process where name="Adobe Audition CC.exe" CALL setpriority "64"
wmic process where name="Iexplorer.exe" CALL setpriority "64"
wmic process where name="OriginThinSetupInternal.exe" CALL setpriority "64"
wmic process where name="OnTopReplica.exe" CALL setpriority "64"
wmic process where name="GAVPI.exe" CALL setpriority "64"
wmic process where name="VoiceAttack.exe" CALL setpriority "64"
wmic process where name="QtWebEngineProcess.exe" CALL setpriority "64"
wmic process where name="OriginWebHelperService.exe" CALL setpriority "64"
wmic process where name="OriginClientService.exe" CALL setpriority "64"
wmic process where name="seamonkey.exe" CALL setpriority "64"
wmic process where name="mic_mute.exe" CALL setpriority "64"
wmic process where name="DriverBooster.exe" CALL setpriority "64"
wmic process where name="notepad++.exe" CALL setpriority "64"
wmic process where name="Lightshot.exe" CALL setpriority "64"
wmic process where name="tweetdeck.exe" CALL setpriority "64"
wmic process where name="pidgin.exe" CALL setpriority "64"
wmic process where name="Winword.exe" CALL setpriority "64"
wmic process where name="Excel.exe" CALL setpriority "64"
wmic process where name="Adguard.exe" CALL setpriority "64"
wmic process where name="OpenIV.exe" CALL setpriority "64"
wmic process where name="ShareX.exe" CALL setpriority "64"
wmic process where name="CCLibrary.exe" CALL setpriority "64"
wmic process where name="AdguardSvc.exe" CALL setpriority "64"
wmic process where name="Adobe Spaces Helper.exe" CALL setpriority "64"
wmic process where name="Vivaldi.exe" CALL setpriority "64"
wmic process where name="IDMan.exe" CALL setpriority "64"
wmic process where name="msaccess.exe" CALL setpriority "64"
wmic process where name="svchost.exe" CALL setpriority "64"
wmic process where name="dllhost.exe" CALL setpriority "64"
taskkill /F /IM explorer.exe
taskkill /F /IM sidebar.exe > NUL
taskkill /F /IM reader_sl.exe
taskkill /F /IM jqs.exe
taskkill /F /IM PhraseExpress.exe
taskkill /F /IM Connectify.exe
taskkill /F /IM vpn-unlimited.exe
taskkill /F /IM ConnectifyGopher.exe
taskkill /F /IM UninstallMonitor.exe
taskkill /F /IM vpn-unlimited-daemon.exe 
taskkill /F /IM IUService.exe
taskkill /F /IM Osa.exe
taskkill /F /IM soffice.exe
taskkill /F /IM MEGAsync.exe
taskkill /F /IM AdobeARM.exe
taskkill /F /IM AAM Update Notifier.exe
taskkill /F /IM Jusched.exe
taskkill /F /IM DivXUpdate.exe
taskkill /F /IM Connectifyd.exe
taskkill /F /IM ConnectifyService.exe
taskkill /F /IM ConnectifyNetServices.exe
taskkill /F /IM DriverSwitcher.exe
taskkill /F /IM ConnectifySupportCenter.exe
taskkill /F /IM wmpnetwk.exe
taskkill /F /IM SkypeHost.exe
taskkill /F /IM GTAVLauncher.exe
taskkill /F /IM GTAVLauncher.exe
wmic process where name="subprocess.exe" CALL setpriority "64"
wmic process where name="HITMAN.exe" CALL setpriority "128"
sc stop uxsms
start %systemroot%\system32\rundll32.exe advapi32.dll,ProcessIdleTasks
cls

:Seeing
@echo off
tasklist /FI "IMAGENAME eq HITMAN.exe" | findstr "HITMAN.exe" >nul
if %ERRORLEVEL% == 1 goto Finish
taskkill /F /IM SkypeHost.exe
taskkill /F /IM SearchUI.exe
taskkill /F /IM GameBarPresenceWriter.exe
taskkill /F /IM GamePanel.exe
timeout 15
@echo Script is live, do not close! Seeing if HITMAN.exe is still running.
goto Seeing

:Finish
@echo off
sc start uxsms
regsvr32 /s msxml3.dll 
regsvr32 /s scrrun.dll
regsvr32 /s jscript.dll
cls
@echo HITMAN.exe no longer active, restoring everything!
timeout 5
start explorer.exe
wmic process where name="svchost.exe" CALL setpriority "32"
wmic process where name="dllhost.exe" CALL setpriority "32"
wmic process where name="services.exe" CALL setpriority "32"
wmic process where name="SecurityHealthService.exe" CALL setpriority "32"
wmic process where name="SecHealthUI.exe" CALL setpriority "32"
wmic process where name="Sidebar.exe" CALL setpriority "normal"
wmic process where name="Firefox.exe" CALL setpriority "normal"
wmic process where name="Lightshot.exe" CALL setpriority "normal"
wmic process where name="tweetdeck.exe" CALL setpriority "normal" 
wmic process where name="Chrome.exe" CALL setpriority "normal"
wmic process where name="GAVPI.exe" CALL setpriority "normal"
wmic process where name="VoiceAttack.exe" CALL setpriority "normal"
wmic process where name="pidgin.exe" CALL setpriority "normal"
wmic process where name="Opera.exe" CALL setpriority "normal"
wmic process where name="Cmd.exe" CALL setpriority "normal"
wmic process where name="wordpad.exe" CALL setpriority "normal"
wmic process where name="OnTopReplica.exe" CALL setpriority "normal"
wmic process where name="Adobe Audition CC.exe" CALL setpriority "normal"
wmic process where name="OriginThinSetupInternal.exe" CALL setpriority "normal"
wmic process where name="QtWebEngineProcess.exe" CALL setpriority "normal"
wmic process where name="OriginWebHelperService.exe" CALL setpriority "normal"
wmic process where name="OriginClientService.exe" CALL setpriority "normal"
wmic process where name="explorer.exe" CALL setpriority "normal"
wmic process where name="Photoshop.exe" CALL setpriority "normal"
wmic process where name="MsMpEng.exe" CALL setpriority "normal"
wmic process where name="Winword.exe" CALL setpriority "normal"
wmic process where name="Excel.exe" CALL setpriority "normal"
wmic process where name="msaccess.exe" CALL setpriority "normal"
wmic process where name="mic_mute.exe" CALL setpriority "normal"
wmic process where name="notepad++.exe" CALL setpriority "normal"
wmic process where name="DriverBooster.exe" CALL setpriority "normal"
wmic process where name="dwm.exe" CALL setpriority "normal"
wmic process where name="SearchUI.exe" CALL setpriority "normal"
wmic process where name="Adguard.exe" CALL setpriority "normal"
wmic process where name="OpenIV.exe" CALL setpriority "normal"
wmic process where name="Vivaldi.exe" CALL setpriority "normal"
wmic process where name="IDMan.exe" CALL setpriority "normal"
wmic process where name="ShareX.exe" CALL setpriority "normal"
wmic process where name="CCLibrary.exe" CALL setpriority "normal"
wmic process where name="AdguardSvc.exe" CALL setpriority "normal"
wmic process where name="Adobe Spaces Helper.exe" CALL setpriority "normal"
wmic process where name="Skype.exe" CALL setpriority "normal"
wmic process where name="upc.exe" CALL setpriority "normal"
wmic process where name="UplayWebCore.exe" CALL setpriority "normal"
wmic process where name="ShellExperienceHost.exe" CALL setpriority "normal" 
wmic process where name="explorer.exe" CALL setpriority "normal"
wmic process where name="Steam.exe" CALL setpriority "normal"
wmic process where name="AsusAudioCenter.exe" CALL setpriority "normal"
wmic process where name="CCleaner64.exe" CALL setpriority "normal"
wmic process where name="ts3client_win64.exe" CALL setpriority "normal"
wmic process where name="Steamwebhelper.exe" CALL setpriority "normal"
wmic process where name="Origin.exe" CALL setpriority "normal"
wmic process where name="Battle.net.exe" CALL setpriority "normal"
wmic process where name="Spotifycrashservice.exe" CALL setpriority "normal"
wmic process where name="Spotifywebhelper.exe" CALL setpriority "normal"
wmic process where name="Spotify.exe" CALL setpriority "normal"
wmic process where name="Uplay.exe" CALL setpriority "normal"
wmic process where name="Sidebar.exe" CALL setpriority "normal"
wmic process where name="Dvm.exe" CALL setpriority "normal"
wmic process where name="Discord.exe" CALL setpriority "normal"
wmic process where name="explorer.exe" CALL setpriority "32"
wmic process where name="MsMpEng.exe" CALL setpriority "32"
wmic process where name="dwm.exe" CALL setpriority "32"
wmic process where name="NisSrv.exe" CALL setpriority "32"
wmic process where name="smartscreen.exe" CALL setpriority "32"
wmic process where name="SearchUI.exe" CALL setpriority "32"
wmic process where name="RadeonSettings.exe" CALL setpriority "32"
wmic process where name="Isass.exe" CALL setpriority "32"
wmic process where name="audiodg.exe" CALL setpriority "32"
wmic process where name="Skype.exe" CALL setpriority "32"
wmic process where name="ShellExperienceHost.exe" CALL setpriority "32" 
wmic process where name="Steam.exe" CALL setpriority "32"
wmic process where name="explorer.exe" CALL setpriority "32"
wmic process where name="Iexplorer.exe" CALL setpriority "normal"
wmic process where name="MicrosoftEdge.exe" CALL setpriority "32"
wmic process where name="MicrosoftEdgeCP.exe" CALL setpriority "32"
exit
