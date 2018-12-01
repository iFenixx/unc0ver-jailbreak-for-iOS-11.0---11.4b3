rc1: Initial release:

rc2: Add the dynastic repo by default and fix a bug in firmware checker

rc3: Add a switch to manually enable restoring RootFS, stop erasing user preferences when restoring RootFS and fix bugs

rc4: Add a label to display the uptime, a label to display the app's version number, spawn to the PATH and stop bundling system fonts

rc5: Run videosubscriptionsd in the jailed state, fix a bug in firmware and update checker

rc6: Start logging again, improve update checker and fix multi_path

rc7: Fix a bug in RootFS Restore and multi_path

rc8: Fix a bug in RootFS Remount and add a work in progress warning for some firmwares

rc9: Fix a bug in RootFS Remount, add even more detailed error messages and add a switch to increase the memory limit to improve the stability and improve the compatibility layer to work correctly with some tweaks that were specifically made for the other jailbreaks

v1: Fix a bug in RootFS Restore and Remount, make the settings tab match with the rest of the UI and fix bugs

v1.0.1: Disable the RootFS Restore for the unstable versions

v1.0.2: Enable and fix the RootFS Restore for all versions

v1.0.3: Fix the beta firmwares

v1.1.0: Automatically select the best exploit, rewrite the versions checker, improve assertion, show the code which has failed in the error messages, improve memory management, optimize and clean up the code, fix the Storage settings, switch to a new technique to disable auto updates, remove so much useless logging, only set the boot-nonce if the switch is on without checking if it exists or not, log offsets, remove static sleeps to improve the speed, fix series of bugs and leave no known bug

v1.1.1: Add a label to show the ECID and a button to open the source code, improve auto layout and fix various bugs in RootFS remount, RootFS restore, RootFS resource copier, Icon cache refresher, Version checker, Exploit selector, jailbreak state detector and others

v1.1.2: Improve auto layout and code and Significantly improve Empty_List (VFS) exploit and slightly improve Multi_Path (MPTCP)

v1.1.3: Fix a bug in starting jailbreakd

v1.1.4: Fix a bug in finding offsets 

v2.0.0 : 11/30/2018 - v2.0.0 was released for public testing with the following changes:

Initial Cydia Substrate support (Requires an updated version of Cydia Substrate which will be released publicly for everyone by Jay Freeman (Saurik) himself at some point), OTA upgrades for the jailbreak patches from Cydia without rebooting, a new button to restart SpringBoard from the jailed state, a switch to (re)install OpenSSH, a switch to reinstall Cydia, a switch to restart backboardd only so that you can jailbreak with broken tweaks, update bootstrap, fix for the jailbreakd error, battery life fixes, ELOD (Electra Loop Of Death) mitigations, improve the speed of system reload, fixes for countless bugs and improvements which I can't remember of right now (We have been working on this update for over a month, I lost the track), I will update the change log as I remember more later

Reminder: You can use the built-in RootFS Restore option to turn your device back to stock

11/30/2018 - v2.0.0 was updated for public testing with the following changes:

Update: The Pre-Release IPA was updated with the following changes: Enable Restart and Restart SpringBoard buttons on iOS 11.4 - 11.4.1 (Jailbreak itself doesn't work on iOS 11.4 - 11.4.1), improve the reliability of the Restart button, fix the broken multi_path entitlement check, add the compatibility layer for the other jailbreaks back to fix the apps like iCleaner and fix the bootstrap error


v1.1.4 Download ipa : https://github.com/pwn20wndstuff/Undecimus/releases/download/v1.1.4/Undecimus.ipa

v2.0.0 Download ipa : https://github.com/pwn20wndstuff/Undecimus/releases/download/v2.0.0/Undecimus.ipa


