<!-- markdownlint-disable MD004 MD024 -->
# Wrapper: Offline Changelog
This changelog is based off [Keep a Changelog](https://keepachangelog.com) and #################### adheres to [Semantic Versioning](https://semver.org/). If you have no idea what that means, basically this changelog is formatted in a specific consistent way, and version numbers are formatted as X.Y.Z, X being a major not-backwards-compatible update, Y being a feature update, and X being bug fixes.

## Version 1.3.4 - 2023-1-24 - YOOO IM BACK!!!
### Added
  - new lil peepz and comedy world assets
### Changed
  - teyeq pull me down is now on stay with me by Swole sauce and spirit link
  - 1.3.0
### Fixed
  - nothing
### Removed (nothing)
  - utilities files, server files and wrapper files unusuals

## Version 1.3.3 - 2022-1-15 - bigger files. IS WAT?
### Added
  - FFDEC version 14.4.0
  - Themelist is at Premade folder
  - Avidemux installer
  - Custom Assets, lil peepz, chibi , cw
  - NCH Recordpad Sound Recorder
### Changed
  - The First Noel is now Egzod & Maestro Chives - Royalty (ft. Neoni) because l hate that song
  - Writing the Future to Elektronomia - Energy cuz sounds like it
  - Remove business themes from gitignore
  - custom_voiceclip.bat : Windows Sound Recorder becomes NCH Recordpad Sound Recorder
  - Node installer becomes v14.17.0
  - License with markdown
  - VFProxy batch : localhost instead of 127.0.0.1
  - Mediainfo 20.03 is now 21.03
  - Avidemux Is now a new version
  - Sourcecode no longer zip
  - http server a new version
  - A new logo
### Fixed
  - Create.html DON'T messed up.
  - Checks Folder because is not here in utilities folder
  - Import files are deleted after opening import.bat so im gonna add import_these folder
  - Discord rpc
### Removed
  - reset_install.bat
  - patch.jpg cuz no one unjk

## Version 1.3.1 - 2021-05-24 - the file size update + stability
## Build 5
### Added
  - Reload settings and metadata option
  - swf.css for page styling
  - Gray cc and cc_browser
### Removed (for cleanup you won't notice a thing)
  - Removed configure_wrapper.bat as it was unnecessary
  - Removed legacy_upgrade_wrapper.bat because there are no more legacy updates being pushed out
  - Removed Git since it's downloaded upon installation
  - Removed included biz themes (why???????)
  - Removed blank Zimmer Twins theme from server\store\3a981f5cb2739137\cc_store
  - Removed 2nd instance of GATOOLS.exe in server\store\3a981f5cb2739137
  - Removed server\store\3a981f5cb2739137\zimmertwins.zip
  - Removed wrapper\data folder
  - Removed help.html
  - Removed Vyond assets
### Changed
  - Compacted theme
  - Renamed VERSIÖN variable in the video list to WRAPPER_VER
  - Recompressed Avidemux, FlashPatch, and 7z1900 to .7z files
  - Grounding script organized
  - Commented list.css
  - Moved version string to the footer like in 1.2.3
### Fixed
  - Updater now checks for .git existence
  - Lil' Peepz actions (thanks JoshToons!)
  - Truncated themelist works in the create page
  - Fixed bug where Wrapper tries to load thumbnails from localhost instead of localhost:4343
  - Updated Wrapper credits
  - Character scaling
## Build 10
### Fixed
  - Updater now checks for .git existence

## Version 1.3.0 - 2021-04-24 - feature packed
## Build 12
### Added
  - Basilisk
  - Exporting workaround using FFMPEG, Avidemux and some virtual drivers
  - Mac files (Unfinished)
  - Upgrade script using Git
  - Google Wavenet and Microsoft Azure voices
  - Dark mode
  - Video list options
  - Power mode
  - Themelist
  - Developer mode
  - Toggle for debug mode
  - Balabolka (see faq.html on how to use the files generated with it)
  - Better support for Trident-based browsers (like IE and Maxthon)
  - Backup/restore tool
  - Action pack selector
### Changed
  - Minor changes to the launcher (version string and crap)
  - Improved CSS
  - Upgraded to the latest build of the GoAnimate-Wrapper source code (1.2.7¾)
  - Code HEAVILY optimized plus more features thanks to the upgrade
### Fixed
  - Importing script not being able to add indenting to the XML
  - Included FFDec timebombed
  - A significant amount of XML corruption glitches thanks to the upgrade
## Build 18
### Changed
  - Imported Assets and Community Library no longer shows the "common" assets
  - Saving a character redirects to the video list instead of refreshing
  - Dark mode tweaked to work (mostly) in the character creator (and browser)
### Fixed
  - CC Browser loading Comedy World no matter what
  - The theme list page being scrambled when dark mode is off
  - A missing page error that can't be refreshed out of
## Build 32
### Added
  - Voice clip importing workaround
### Changed
  - Version string format changed
### Fixed
  - Every single function showing everytime the export video script opens "start_wrapper.bat".

## Version 1.2.3 - 2021-03-06 - i am HUNGRY FOR UPDATES!!!
### Added
  - Character browser
  - Truncated themelist
  - Character uploading
  - Discord RPC
### Changed
  - Centered character creator
### Fixed
  - Remove the Voicery TTS engine following their shutdown
  - Voiceforge fix AKA VFProxy
  - Fullscreen in video player
  - Effects
  - Fixed header shrinking

## Version 1.2.2 - 2020-07-06 - sufferingggggg
### Changed
  - CD commands are now PUSHD commands
  - Open Node.js/http-server scripts show helpful messages when closing
### Fixed
  - Import script now detects whether the file directory has quotes
  - Import script no longer loops when asking questions
  - Import script specifically only checks files in the base folder, no subfolders
  - Upgrade comes with node_modules folder to stop MODULE_NOT_FOUND errors
  - Taskkill errors are now muted

## Version 1.2.1 - 2020-07-06 - weeeeee bug fixes
### Changed
  - Upgrade script just checks for file existence instead of using variables
### Fixed
  - Importer now copies to _THEMES folder
  - Reverted use of CHOICE command because people were having issues with it
  - Punch action now doesn't look horrible (credit to creepyjokes2000)
  - Launcher creates checks folder if nonexistent
  - Removed chcp 65001 from files that don't need it to prevent crashing
  - HTTPS cert now checks for the right file
  - Old music/sfx are back

## Version 1.2.0 - 2020-07-05 - a launcher overhaul disguised as the file importing update
### What do I care about
This update basically has file uploading. New TTS voices have been added, including Eric and Jennifer. The headgear section works now. Waveforms work now. Mega Comedy World 2 has been added. An FAQ is now included with Wrapper. The launcher is far more stable now, as you can tell from all the entries that start with the word Launcher.
### Added
  - File uploading!!!...kinda. It's more of a workaround.
  - Loads of new TTS voices (yes this means eric and jennifer)
  - Mega Comedy World 2 by Blukas/GoTube
  - Functioning waveforms (credit to creepyjokes2000)
  - Headgear sections (credit to JoshAnimate)
  - Frequently Asked Questions file/page (#answers from the discord server)
  - Disclaimer when launching for the first time
  - Folder in utilities that stores files to remember certain events
  - Added script for resetting your install (meant for developers)
  - Dry run option for testing launcher easier
  - Non-admin HTTPS cert install option (but admin is still preferred)
  - Source code of programs is now included in utilities folder
  - Chromium now includes Requestly and Stylus extensions
  - Copy of JPEXS Free Flash Decompiler included
  - Upgrade script
### Changed
  - Turned on "use gpu" in Flash attributes. May or may not do anything, who knows
  - Settings is now interactive (text version still in utilities\config.bat, but you probably shouldn't mess with it)
  - Heavily modified the README (mostly simplifying and moving things to faq.txt)
  - Video list mostly redone
  - Server page redone
  - HTTPS cert now also applies to server ports both 4664 and 4343
  - HTTPS cert now expires on 9999-12-31 instead of 4343-04-03, just to be extra sure that by the time it expires technology will have advanced so far that HTTPS will only exist as a relic of history and most if not all of Wrapper: Offline's functions will only be possible in an emulated version of today's technology. if that prediction turns out to be completely false someone can just renew it and be done so 10,000s kids can still make grounded videos on youtube
  - Node.js installer is now 12.18.1
  - Flash installer is now 32.0.0.371
  - Launcher explicitly mentions verbose mode is on while idle
  - Launcher checks for HTTPS cert check more reliably
  - Launcher variables now use y/n instead of yes/no
  - Launcher admin required prompt specifies what is needed
  - Launcher single key choices now use choice command
  - Launcher open README command now opens FAQ
  - Launcher idle options reorganized
  - Launcher server page option now opens in Chromium if enabled
  - Launcher turns on skipping dependency check if all are found
### Fixed
  - Sprint action looks less broken (credit to creepyjokes2000)
  - patch. it's in the utilities folder, don't move it next to the launcher
  - HTML injection was possible via the Upload a Movie button
  - More voices should now fit within the character limit
  - All scripts use UTF-8 to prevent special character crashes
  - Server's port is now 4664 instead of 4343, Wrapper port is 4343 instead of 80 (hopefully will prevent EADDRINUSE errors)
  - Launcher now closes any running Node.js processes (hopefully also prevents EADDRINUSE)
  - Launcher should no longer crash from running as Admin
  - Launcher now checks if it's in a Wrapper: Offline folder
  - Launcher waits before opening your browser to allow Wrapper to start up
  - Launcher now kills Edge and Brave when installing Flash
  - Launcher can now generate settings if not available
  - Launcher now finds more Flash versions and is more aware of settings
  - Launcher now checks if installers exist before running them
  - Launcher stays open when crashing to be troubleshooted
  - Launcher no longer crashes from spaces in answers
  - Launcher now switches drives when moving to W:O folder
  - Launcher variables now use delayed expansion syntax
  - Launcher now opens server page in HTTPS properly

## Version 1.1.2 - 2020-05-12 - someday i'll learn to not rush releases
### Changed
  - Node.js/http-server scripts make sure they're in the right folder
### Fixed
  - 1.1.0's download wasn't reset for a clean install

## Version 1.1.1 - 2020-05-12 - "the launcher works in this one" part sequel the continuation
### Changed
  - Node.js/http-server script titles show if it hasn't launched yet
### Fixed
  - Launcher would crash from trying to load a setting before settings were loaded

## Version 1.1.0 - 2020-05-12 - An Acceptable Archive Area
### What do I care about
The character folder is now compressed, resulting in MUCH smaller file sizes. This changelog exists so it's easy to see what was changed in each update. The character creator goes to the video list after saving.
### Added
  - Characters folder compression
  - This changelog
### Changed
  - Character loading error catching loads Benson, and simply 404s if that fails
  - Reorganized the character creator dropdown
  - Switched from 127.0.0.1:4343 to localhost:4343 for server page (basically no difference, just cleaner)
  - HTTPS cert updated with contact email, proper name, and being valid for both 127.0.0.1 and localhost
  - Extra CMD windows are now hidden (unless in verbose mode)
    - To do this, the utilities folder has scripts to launch Node.js and http-server individually
  - Launcher title shows what stage it's in
  - HTML page files reorganized
### Fixed
  - Launcher doesn't crash after installing http-server
  - Character creator now goes to the video list after saving
  - README is now accurate and doesn't have my unfufilled dreams in it
  - Launcher shows the proper version number this time
  - Closing the launcher with CTRL+C is blocked

## Version 1.0.2 - 2020-04-18 - can you tell i kinda rushed 1.0.0
### Fixed
  - Video player would not load

## Version 1.0.1 - 2020-04-18 - "the launcher works in this one" edition
### Fixed
  - Launcher not starting in wrapper-offline folder while running as Admin

## Version 1.0.0 - 2020-04-18 - Is ready?
Initial release

## Version 0.1.0 - never happened
i wish it did why did i start on 1.0.0
fair i didn't realize how much of wrapper was truly buggy at the time but fuckkkkkkkkkkkkkkkkkkkkkkkk

## Version 0.0.1 - ...
Not Found
HTTP Error 404. The requested resource is not found.

