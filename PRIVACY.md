## Offline Buddy: Privacy policy

Welcome to the Offline Buddy app for Android.

### Data collected by the app

This app does not collect, store or share any personally identifiable information.
Data internal to the app (such as program preferences) is stored locally on the device. Some information may be exchanged with the app on the buddy device, but this is still data internal to Offline Buddy.

### Permissions requested in the app
These permissions are used by the app:
<br/>

| Permission | Why it is required |
| --- | --- |
| `BLUETOOTH` , `BLUETOOTH_CONNECT`| Basic requirment of the app to use Bluetooth. Without these permissions the app cannot function. |
| | |
| `POST_NOTIFICATIONS`| Allows the app to notify the user of connection and disconnection events. The use of a foreground service (see below) requires the app to notify the user that it is active. Without this permission the app cannot function. However, app notifications can be controlled by the user via Android Settings.|
| | |
| `FOREGROUND_SERVICE` , `FOREGROUND_SERVICE_CONNECTED_DEVICE`| A foreground service is used to keep the connection between buddies alive.  Automatically granted by the system; cannot be revoked by the user.|
| | |
| `WAKE_LOCK`| Needed to prevent the device going to sleep while buddies are connected.  Automatically granted by the system; cannot be revoked by the user.|
| | |
| `DEVICE_ADMIN`| Requested if the screen locking option is enabled. If the permission is granted, the app becomes registered as a device admin app. Conversely, if the option was enabled and is disabled, the app is de-registered as an admin app. Be aware that while the app is registered as a device admin app it cannot be uninstalled. If uninstallation is required, either turn off the locking option in the app settings, or use the Android app settings to remove the device admin authority.|

If you have any query regarding privacy or security in the app, you can contact me at offlinebuddy@ceperman.com

Chris Wood 2025
