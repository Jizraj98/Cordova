# Android SDK Artifacts

## How to use repository

1. Ensure that the latest commit from the 'master' branch has been pulled.

2. Artifacts are arranged in the format:

```
idp-android-sdk-artifacts/
   ├── README.md                             # overview of the sdk
   ├── ble-sdk/                       
   │   └── <artifact-version>/               # sdk artifact version, e.g. 3.66.10
   │       └── sample-app/            	      # sdk demo application
   │       └── <artifact.aar>         	      # sdk's android library file
```

## Updates

3.66.10 
- Supports more locks and accessories, including enterprise locks
- Please note that function parameters' type for time has been changed from 'Int' to 'Long' 

2.56.3 Added x86 and x86_64 into abiFilters
- Merely for those who need the SDK to work with x86/x86_64 Android
- Everything else are the same as 2.56.2

2.56.2 Supports Android 12
- Added the new BLUETOOTH_SCAN and BLUETOOTH_CONNECT permissions in the manifest, for app targeted Android 12 and above. 
- Maintained the existing BLUETOOTH, BLUETOOTH_ADMIN and ACCESS_FINE_LOCATION permissions in the manifest for app targeted Android 11 and below.

