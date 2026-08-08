
# iOS 27.0 Carrier Bundles

This repo contains the Carrier Bundles currently bundled with iOS version 27.0 for the iPhone 17 Pro Max.
## Last Extraction Metadata

#### Last Extraction Time
`2026-08-08 00:50:50 UTC`

#### iOS Build Info

| iOS Version | iOS Build | iOS Build Timestamp |
| :-------- | :------- | :------------------ |
| 27.0 | 24A5390f | 11 Jul 2026 04:29:00 UTC |

#### iOS Device Info

| Device Name | Device Identifier |
| :-------- | :------- |
| iPhone 17 Pro Max | iPhone18,2 |

## Folder Explanations

#### Carrier Bundles
This folder contains the Carrier Bundles specific to each carrier.

On the iOS filesystem, this folder can be found at:
```
/System/Library/Carrier Bundles/iPhone
```

These files are extracted from Apple's binary plist format and stored here as XML so changes are readable in GitHub diffs.

[The Apple Wiki](https://theapplewiki.com/) has further information on [Carrier Bundles](https://theapplewiki.com/wiki/Carrier_Bundle).

#### Country Bundles
This folder contains the Carrier Bundles that apply to all carriers within a country.

On the iOS filesystem, this folder can be found at:
```
/System/Library/CountryBundles/iPhone/
```

These files are extracted from Apple's binary plist format and stored here as XML so changes are readable in GitHub diffs.

## Acknowledgements
 - [blacktop/ipsw](https://github.com/blacktop/ipsw)
 - [sgan81/apfs-fuse](https://github.com/sgan81/apfs-fuse)