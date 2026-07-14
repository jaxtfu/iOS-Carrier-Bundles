
# iOS (IOS_VERSION) Carrier Bundles

This repo contains the Carrier Bundles currently bundled with iOS version (IOS_VERSION) for the (DEVICE_NAME).
## Last Extraction Metadata

#### Last Extraction Time
`(CURRENT_DATE)`

#### iOS Build Info

| iOS Version | iOS Build | iOS Build Timestamp |
| :-------- | :------- | :------------------ |
| (IOS_VERSION) | (IOS_BUILD) | (IOS_BUILD_TIMESTAMP) |

#### iOS Device Info

| Device Name | Device Identifier |
| :-------- | :------- |
| (DEVICE_NAME) | (DEVICE_PRODNAME) |

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