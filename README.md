# Lulzbot-Taz3-Marlin-Update
Documents updating the Lulzbot Taz 3 to the latest Marlin firmware. 

I chose to use the LTS version
https://github.com/MarlinFirmware/Marlin/tree/2.0.9.6

Marlin Firmware can be downloaded here:
https://marlinfw.org/meta/download/

In the Marlin subdirectory, setup the configuration files

Marlin-2.0.x -> Marlin

Create files 
- Configuration.h
- Configuration_adv.h

# Save Existing Settings
On your TAZ LCD screen save your Configuration settings

For my TAZ 3.

Motion
Accel 500
Vxy jerk 8
Vz jerk +0.40
Ve-jerk 10
Vmax x 800
Vmax y 800
Vmax z 3
Vmax e 50
Vmin 0
VTrav min 0 
Amax x 9000
Amax y 9000
Amax z 100
Amax e 10000A-retract 3000
Xsteps/mm 100.50
Ysteps/mm 100.50
Zsteps/mm 0800.0
Esteps/mm 0846.0

# Saving Previous Firmware

Use AVRDUDESS 2.14


References
- https://github.com/drunken-octopus/drunken-octopus-marlin
- https://forum.lulzbot.com/t/how-to-build-firmware-from-https-gitlab-com-lulzbot3d-marlin/24438/1
- https://docs.google.com/document/d/1NB3hsBLC33MJt-7gompC4JbloByG3KxmuD2u5_FsABg/edit
- https://github.com/jjaeggli/prusaslicer-lulzbot-taz
- https://forum.lulzbot.com/t/differences-between-lulzbot-taz-models-1-2-3-4-5-6/2736
- https://e3d-online.zendesk.com/hc/en-us/articles/4411538595345-How-to-install-VS-Code-and-prepare-Marlin-2-0

