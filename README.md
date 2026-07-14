# ValueCam Firmware Updater

Public binary releases for the ValueCam ESP32-P4 camera.

Use the owner updater at:

<https://conntrace.github.io/valuecam-firmware/>

The site installs the current firmware over USB with ESP Web Tools and includes
the brief owner manual and all 44 mode descriptions. The mode reference uses
category tabs and a fixed scroll area so filtering does not shift the page.
Normal non-erase updates preserve camera settings. `VALUECAM_SD.BIN` is the
microSD fallback image; rename it to `VALUECAM.BIN` on the card. `SHA256SUMS`
contains release checksums.

Firmware source is maintained separately and is not published in this binary
release repository.
