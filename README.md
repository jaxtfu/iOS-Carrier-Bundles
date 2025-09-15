
# iOS 26.0 Carrier Bundles

This repo contains the Carrier Bundles currently bundled with iOS version 26.0 for the iPhone 16 Pro.
## Last Extraction Metadata

#### Last Extraction Time
`2025-09-15 20:46:31 UTC`

#### iOS Build Info

| iOS Version | iOS Build | iOS Build Timestamp |
| :-------- | :------- | :------------------ |
| 26.0 | 23A341 | 26 Aug 2025 03:47:22 UTC |

#### iOS Device Info

| Device Name | Device Identifier |
| :-------- | :------- |
| iPhone 16 Pro | iPhone17,1 |

## Folder Explanations

#### Carrier Bundles
This folder contains the Carrier Bundles specific to each carrier.

On the iOS filesystem, this folder can be found at:
```
/System/Library/Carrier Bundles/iPhone
```

These files are in Apple's binary plist format, so you will need an editor that can handle these kinds of files to view them.

[The Apple Wiki](https://theapplewiki.com/) has further information on [Carrier Bundles](https://theapplewiki.com/wiki/Carrier_Bundle).

#### Country Bundles
This folder contains the Carrier Bundles that apply to all carriers within a country.

On the iOS filesystem, this folder can be found at:
```
/System/Library/CountryBundles/iPhone/
```

These files are in Apple's binary plist format, so you will need an editor that can handle these kinds of files to view them.

## Acknowledgements
 - [blacktop/ipsw](https://github.com/blacktop/ipsw)
 - [sgan81/apfs-fuse](https://github.com/sgan81/apfs-fuse)