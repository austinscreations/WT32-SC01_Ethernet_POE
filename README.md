# WT32-SC01_POE

2023-06-28:

New sheild has been designed that is more universal. the deisgn is much smaller. uses a single 1.25mm jst conenctor to connect to the wt32-sc01 PLUS display.
adapter has been built for the WT32-S3-86s (replaces the 86v) 4" display. adapter in the works to support the orginal display as well

2022-06-23: renamed the repo as this project has evolved

There are now two shields designed for the wt32-sc01 display.
- one offers Ethernet + 802.1af POE
- second offers passive 12-24v POE + a 2.1mm jack

the thought with a passive board is that it's smaller allowing for more compact case designs to be built. and if you prefer to use 802.1af POE with the 2.1mm jack you can very eaily use a standard POE injector that normally cost about $6 from aliexpress to gain such functionality. with teh apssive baord however you are limited to using wifi.

both shields also equipped with qwiic connector for easy i2c support

designed for the use case of using the panel for homeautomation, code and gui in progress.
