# MeltStealer

MeltStealer is a C# data extraction tool that grabs and "steals" files such as passwords, wallets, extensions, files, system information, geolocation, app data, and much more.

Please be aware that this tool is purely for demonstration purposes and should not be used for any illegal or malicious activity. I do not support any misuse of this software for any purpose that is not educational or on your own system. Any misuse will result in restriction from the tool.

The main code for this tool is from StormKitty; however, StormKitty was severely lacking in features, so I updated it with new features such as:
- Grabbing all extensions (including wallets)
- Sending a detailed Telegram message along with a zip file containing all grabbed information
- Wallet injection to grab the mnemonic key and password of multiple crypto applications

All other features of StormKitty remain the same. StormKitty includes features such as:
- Anti-analysis (VirtualBox, Sandbox, Emulator, Debugger, VirusTotal, Any.Run)
- Stealing system info (version, CPU, GPU, RAM, IPs, BSSID, location, screen metrics)
- Chromium-based browsers (passwords, credit cards, cookies, history, autofill, bookmarks)
- Firefox-based browsers (db files, cookies, history, bookmarks)
- Internet Explorer/Edge (passwords)
- Saved Wi-Fi networks and scanning networks around the device (SSID, BSSID)
- Detecting banking and cryptocurrency services in browsers
- Installing keylogger and clipper
- Steam, Uplay, Minecraft session
- Desktop and webcam screenshot
- ProtonVPN, OpenVPN, NordVPN
- Cryptocurrency wallets
- Telegram sessions
- Pidgin accounts
- Discord tokens
- FileZilla hosts
- Process list
- Directories structure
- Product key
- Autorun module

Setup:
Download the latest release
Extract all contents to a directory
Run the builder and enter a Telegram bot API token and chat ID. The bot token can be created with @BotFather (just create a bot and start it) on Telegram, and the chat ID can be viewed from @getidsbot
Build the file; the build will appear in the stub folder
Done! Make sure the built file remains in the same directory as the DLL, or injection will fail and the executable will throw errors.

Please remember that this tool is not to be used in any illegal activity. I do not allow any misuse. This is purely for use on your own system or for education and malware analysis.


