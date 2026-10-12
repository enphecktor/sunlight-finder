# Sunlight finder

Finds a Sunlight dimmer (WLED + Sun Curve firmware) over Bluetooth LE, reads its
current IP address, and opens the app at `http://<ip>/sun.htm`.

- Open in a browser with Web Bluetooth: **Bluefy** on iPad/iPhone, Chrome on Android/desktop.
- The device must be on the same Wi-Fi as the dimmer.
- Falls back to `http://dimmer.local/sun.htm` or the last address found.

BLE service `5a7e0001-6c1a-4d2f-9b3e-53756e4c6974`
(ip `...0002`, url `...0003`, both read-only strings).
