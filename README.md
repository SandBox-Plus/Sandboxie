Sandboxie Plus / Classic

Plus license Classic license GitHub Release GitHub Pre-Release GitHub Build Status GitHub Codespell Status

Join our Discord Server
System requirements 	Release notes 	Contribution guidelines 	Security policy 	Code of Conduct
Windows 7 or higher, 32-bit or 64-bit. 	CHANGELOG.md 	CONTRIBUTING.md 	SECURITY.md 	CODE_OF_CONDUCT.md

Sandboxie is a sandbox-based isolation software for 32-bit and 64-bit Windows NT-based operating systems. It creates a sandbox-like isolated operating environment in which applications can be run or installed without permanently modifying local & mapped drives or the Windows registry. An isolated virtual environment allows controlled testing of untrusted programs and web surfing.

Sandboxie allows you to create virtually unlimited sandboxes and run them alone or simultaneously to isolate programs from the host and each other, while also allowing you to run as many programs simultaneously in a single box as you wish.

Note: This is a community fork that took place after the release of the Sandboxie source code and not the official continuation of the previous development (see the project history).
⏬ Download

Latest Release
🚀 Features

Sandboxie is available in two editions, Plus and Classic. They both share the same core components, this means they have the same level of security and compatibility. What's different is the availability of features in the user interface.

Sandboxie Plus has a modern Qt-based UI, which supports all new features that have been added since the project went open source:

    Snapshot Manager - takes a copy of any box in order to be restored when needed
    Maintenance mode - allows to uninstall/install/start/stop Sandboxie driver and service when needed
    Portable mode - you can run the installer and choose to extract all files to a directory
    Additional UI options to block access to Windows components like printer spooler and clipboard
    More customization options for Start/Run and Internet access restrictions
    Privacy mode sandboxes that protect user data from illegitimate access
    Security enhanced sandboxes that restrict the availability of syscalls and endpoints
    Global hotkeys to suspend or terminate all boxed processes
    A network firewall per sandbox which supports Windows Filtering Platform (WFP)
    The list of sandboxes can be searched with the shortcut key Ctrl+F
    A search function for Global Settings and Sandbox Options
    Ability to import/export sandboxes to and from 7z files
    Integration of sandboxes into the Windows Start menu
    A browser compatibility wizard to create templates for unsupported browsers
    Vintage View mode to reproduce the graphical appearance of Sandboxie Control
    A troubleshooting wizard to assist users with their problems
    An Add-on manager to extend or add functionality via additional components
    Protections of sandboxes against the host, including the prevention of taking screenshots
    A trigger system to perform actions, when a sandbox goes through different stages, like initialization, box start, termination or file recovery
    Make a process not sandboxed, but its child processes sandboxed

More features can be spotted by finding the sign = through the shortcut key Ctrl+F in the CHANGELOG.md file.

Sandboxie Classic has the old no longer developed MFC-based UI, hence it lacks native interface support for Plus features. Although some of the missing features can be configured manually in the Sandboxie.ini configuration file or even replaced with custom scripts, the Classic edition is not recommended for users who want to explore the latest security options.
📚 Documentation

A GitHub copy of the Sandboxie documentation is currently maintained, although more volunteers are needed to keep it updated with the new changes. We recommend to check also the following labels in this repository:

future development | feature requests | documentation | build issues | incompatibilities | known issues | regressions | workaround | help wanted | more...

A partial archive of the old Sandboxie forum that was previously maintained by Invincea is still available. If you need to find something specific, it is possible to use the following search query: site:https://sandboxie-website-archive.github.io/www.sandboxie.com/old-forums/
🚀 Useful tools for Sandboxie

Sandboxie's functionality can be enhanced with specialized tools like the following:

    LogApiDll - adds a verbose output to Sandboxie's trace log, listing invocations of relevant Windows API functions
    SbieHide - attempts to hide the presence of SbieDll.dll from the application being sandboxed
    SandboxToys2 - allows to monitor files and registry changes in a sandbox
    Sbiextra - adds additional user mode restrictions to sandboxed processes

📌 Project history
Timeline 	Maintainer
2004 - 2013 	Ronen Tzur
2013 - 2017 	Invincea Inc.
2017 - 2020 	Sophos Group plc
Open-source code 	Tom Brown
2020 onwards 	David Xanatos (Roadmap)
📌 Project support / sponsorship

Thank you Vector 35 for providing a Binary Ninja license to help with reverse engineering.
Binary Ninja is a multi-platform interactive disassembler, decompiler, and binary analysis tool for reverse engineers, malware analysts, vulnerability researchers, and software developers.

Thank you Icons8 for providing icons for the project.


🤝 Support the project

If you find Sandboxie useful, then feel free to contribute through our Contribution guidelines.
📑 Helpful Contributors

    DavidBerdik - Maintainer of Sandboxie Website Archive
    Jackenmen - Maintainer of Chocolatey packages for Sandboxie (support)
    vedantmgoyal9 - Maintainer of Winget Releaser for Sandboxie (support)
    blap - Maintainer of SandboxToys2 addon
    diversenok - Security analysis & PoCs / Security fixes
    TechLord - Team-IRA / Reversing
    hg421 - Security analysis & PoCs / Code reviews
    hx1997 - Security analysis & PoC
    mpheath - Author of Plus installer / Code fixes / Collaborator
    offhub - Documentation additions / Code fixes / Collaborator
    isaak654 - Templates / Documentation / Code fixes / Collaborator
    typpos - UI additions / Documentation / Code fixes
    Yeyixiao - Feature additions
    Deezzir - Feature additions
    okrc - Code fixes
    Sapour - Code fixes
    lmou523 - Code fixes
    sredna - Code fixes for Classic installer
    weihongx9315 - Code fix
    jorgectf - CodeQL workflow
    stephtr - CI / Certification
    yfdyh000 - Localization support for Plus installer
    Dyras - Templates additions
    cricri-pingouin - UI fixes
    Valinwolf - UI / Icons
    daveout - UI / Icons
    NewKidOnTheBlock - Changelog fixes
    Naeemh1 - Documentation additions
    APMichael - Templates additions
    1mm0rt41PC - Documentation additions
    Luro223 - Documentation additions
    lwcorp - Documentation additions
    wilders-soccerfan - Documentation additions
    LumitoLuma - Qt5 patch and build script

🌏 Translators

    yuhao2348732, 0x391F, nkh0472, yfdyh000, gexgd0419, Zerorigin, UnnamedOrange, DevSplash, Becods, okrc, 4rt3mi5, sepcnt - Simplified Chinese
    TragicLifeHu, Hulen, xiongsp - Traditional Chinese
    RockyTDR - Dutch
    clexanis, Mmoi-Fr, hippalectryon-0, Monsieur Pissou - French (provided by email)
    bastik-1001, APMichael - German
    timinoun - Hungarian (provided by email)
    isaak654, DerivativeOfLog7 - Italian
    takahiro-itou - Japanese
    VenusGirl - Korean
    7zip - Polish (provided separately)
    JNylson - Portuguese and Brazilian Portuguese
    lufog - Russian
    LumitoLuma, sebadamus - Spanish
    1FF, Thatagata - Swedish (provided by email or pull request)
    xorcan, fmbxnary, offhub - Turkish
    SuperMaxusa, lufog - Ukrainian
    GunGunGun - Vietnamese

All translators are encouraged to look at the Localization notes and tips before sending a translation.
