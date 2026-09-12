# Samsung Galaxy A70 firmware

This repository contains the device-specific, signed firmware needed by the
mainline Linux port for the Samsung Galaxy A70 (SM-A705FN, `a70q`). It is kept
as a minimal source archive for the postmarketOS `firmware-samsung-a70q` aport.

Included firmware:

- ADSP metadata, split ELF segments, and JSON service metadata
- Adreno 612 board-specific ZAP shader firmware
- WCN3988 Bluetooth rampatch and board NVM
- WCN3990 Wi-Fi board calibration data
- Venus video firmware

Generic Adreno RGMU and SQE firmware and common WCN3990 Wi-Fi firmware are
deliberately not duplicated here. The aport obtains those files from the
upstream `linux-firmware` packages.

The files were extracted from the public Samsung Galaxy A70 firmware set used
by LineageOS. They are proprietary binary firmware; redistribution terms may
vary. The Wi-Fi calibration is board-specific, not handset-specific. No modem
EFS, IMEI, MAC address, or other per-device data is included.
