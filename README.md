# Samsung Galaxy A70 firmware

This repository contains the device-specific, signed firmware needed by the
mainline Linux port for the Samsung Galaxy A70 (SM-A705FN, `a70q`). It is kept
as a minimal source archive for the postmarketOS `firmware-samsung-a70q` aport.

Included firmware:

- ADSP metadata, split ELF segments, and JSON service metadata
- Adreno 612 board-specific ZAP shader firmware
- Venus video firmware

Generic Adreno RGMU and SQE firmware is deliberately not duplicated here. The
aport obtains those files from a pinned release of the upstream
`linux-firmware` repository.

The files were extracted from the public Samsung Galaxy A70 firmware set used
by LineageOS. They are proprietary binary firmware; redistribution terms may
vary. No modem EFS, calibration, IMEI, or per-device data is included.
