# Samsung Galaxy A70q Firmware

Firmware blobs extracted from LineageOS 22.2 for Samsung Galaxy A70 (SM-A705FN).

## Contents

### GPU (Adreno 612)
- `adreno/a612_rgmu.bin` - A612 GMU firmware
- `adreno/a618_gmu.bin` - A618 GMU firmware  
- `adreno/a630_gmu.bin` - A630 GMU firmware
- `adreno/a630_sqe.fw` - Sequence engine firmware
- `adreno/a640_gmu.bin` - A640 GMU firmware

### Bluetooth (Qualcomm)
- `qca/apbtfw11.tlv` - Bluetooth firmware
- `qca/apnv11.bin` - Bluetooth NV data

### WiFi (Qualcomm WCN3990)
- `wlan/bdwlan.bin` - WiFi firmware
- `wlan/regdb.bin` - Regulatory database

### IPA (Internet Packet Accelerator)
- `ipa/ipa_fws.mdt` - IPA metadata
- `ipa/ipa_fws.b00-b04` - IPA firmware segments

## Source

Extracted from Samsung Galaxy A70 (SM-A705FN) vendor partition:
- LineageOS 22.2 (unofficial) build date: 2025-11-02
- Firmware version: A705FNXXU5DWB4

## Usage

For postmarketOS firmware package. Install to `/lib/firmware/` paths as appropriate.

## License

Proprietary Samsung/Qualcomm firmware. Redistribution terms unclear.
