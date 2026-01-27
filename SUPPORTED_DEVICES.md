# Supported Devices

**Stability**
* *untested* - this image has not been tested on hardware. It may or may not work.
* *stable* - this image has been tested on hardware. There may still be bugs.

**Status**
* *released* - this image is in a production release of the +tiny firmware.
* *nightly* - this device is newly supported in the nightly builds (since the last production release).
* *sunset* - this device is supported but no longer recommended for new purchases or installs.
* *brick* - this image has been tested and found to brick your hardware. Avoid for now.
* *not supported* - this image is not supported and not available for download.
* *frozen* - this device has been previously sunsetted, and is now frozen. Old images are still available but there will be no future updates.

The 'target' and 'subtarget' identify the directory in which to find the image at <http://downloads.k3pgm.radio/>

## Ubiquiti
Model | SKUs | Band | Target | Subtarget | Image | RAM | Stability | Status
:------ | :----: | :----: | :------: | :---------: | :-----: | :---: | :---------: | :------
**+tiny Devices** | | | | | | | |
AirGrid M2 XM || 2 | ath79 | tiny (1) | ubnt_bullet-m-ar7241 | 32MB | untested | released
AirGrid M5 XM || 5 | ath79 | tiny (1) | ubnt_bullet-m-ar7241 | 32MB | untested | released
AirRouter || 2 | ath79 | tiny (1) | ubnt_airrouter | 32MB | stable (2) | released
AirRouter HP || 2 | ath79 | tiny (1) | ubnt_airrouter | 32MB | stable (2) | released
Bullet M5 || 5 | ath79 | tiny (1) | ubnt_bullet-m-ar7241 | 32MB | untested | released
Bullet M2 || 2 | ath79 | tiny (1) | ubnt_bullet-m-ar7241 | 32MB | stable | released
NanoBridge 2G18 || 2 | ath79 | tiny (1) | ubnt_nanobridge-m | 32MB | untested | released
NanoBridge 5G22 || 5 | ath79 | tiny (1) | ubnt_nanobridge-m | 32MB | stable | released
NanoBridge 5G25 || 5 | ath79 | tiny (1) | ubnt_nanobridge-m | 32MB | stable | released
NanoBridge M9 || 900 | ath79 | tiny (1) | ubnt_nanostation-loco-m | 32MB | stable | released
NanoStation Loco M2 XM || 2 | ath79 | tiny (1) | ubnt_nanostation-loco-m | 32MB | stable | released
NanoStation Loco M5 XM || 5 | ath79 | tiny (1) | ubnt_nanostation-loco-m | 32MB | untested | released
NanoStation Loco M9 XM || 900 | ath79 | tiny (1) | ubnt_nanostation-loco-m | 32MB | stable | released
NanoStation M2 XM || 2 | ath79 | tiny (1) | ubnt_nanostation-m | 32MB | stable | released
NanoStation M3 XM || 3 | ath79 | tiny (1) | ubnt_nanostation-m | 32MB | stable | released
NanoStation M5 XM || 5 | ath79 | tiny (1) | ubnt_nanostation-m | 32MB | stable | released
PicoStation M2 || 2 | ath79 | tiny (1) | ubnt_picostation-m | 32MB | untested | released


## Footnotes
 1. Tiny builds exclude support for *tunnels* and *WiFi AP* mode due to lack of resources. The relevant packages can be installed separately but this is not recommended.
 2. The AirRouter works but performs poorly and may sporadically reboot. Not recommended.

+tiny builds are available from: <http://downloads.k3pgm.radio/afs/www/>

Latest installation instructions are found at: <https://docs.arednmesh.org/en/latest/>
