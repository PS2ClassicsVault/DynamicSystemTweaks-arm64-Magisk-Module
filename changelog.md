Donations:
https://www.paypal.me/CyberGamingStudios

If you encounter bug or issue please submit a new issue ticket!

# v1.5
- Increased dex2oat thread count processing to use 6 cores instead of 4 cores
- Set hwui OpenGL to use vulkan
- Set wifi scan to 200 instead of 180 for better power saving
- Added bluetooth improvementa for controllers
- Added tweaks to improve USB connectivity performance for controllers.
- Added tweaks to force games to 60Hz by default
- Improved network code for better net performance
- Set windowsmgr per sec to 60fps min and 120fps max

# v1.4
- Improved performance
- Improved tweaks
- Decreased dex2oat thread count from 8 to 4

# v1.3
- Removed HWUI tweaks as it contributed to slowing the OS down a bit.
- Improved ART compiling for applications.
- Added dalvik lockprof tweak and set it to 500.
- Improved system performance when module us being used.

# v1.2
- Reduced egl buffer from 4 to 3.
- Reworked module to ensure system stability and performance.
- Added HWUI configuration for UI smoothness.
- Fixed an issue where the syatem fps would sometimes drop under 60fps even though devices with a 90Hz or higher display.
- Set storage manager on by default.
- Enabled firmware trimming.
- Reduced footprint size of system prop.

# Note: 
If you experience any bugs please report them so i can apply any hotfix to them.