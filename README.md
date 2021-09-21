A kinda optimal TLP config for Ryzen 5 3500U in Honor MagicBook D14 2020. Note: I'm using Fedora 34 Cinnamon.

Uncommented the following lines and chose the following parameters (subject to change, please actually read the tlp.conf text file):

* TLP_ENABLE=1

* CPU_SCALING_GOVERNOR_ON_AC=schedutil

* CPU_SCALING_GOVERNOR_ON_BAT=powersave

* CPU_BOOST_ON_AC=1

* CPU_BOOST_ON_BAT=0

* SCHED_POWERSAVE_ON_AC=0

* SCHED_POWERSAVE_ON_BAT=1

* RADEON_POWER_PROFILE_ON_AC=default

* RADEON_POWER_PROFILE_ON_BAT=default

* RADEON_DPM_STATE_ON_AC=performance

* RADEON_DPM_STATE_ON_BAT=battery

* RADEON_DPM_PERF_LEVEL_ON_AC=auto

* RADEON_DPM_PERF_LEVEL_ON_BAT=auto

* START_CHARGE_THRESH_BAT0=75

* STOP_CHARGE_THRESH_BAT0=80
