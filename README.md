# OpenWireGuard
## A startup helper for the macOS WireGuard VPN Client.
The [original macOS WireGuard Client](https://apps.apple.com/de/app/wireguard/id1451685025?mt=12) 
unfortunately comes with an annoying bug: 

The GUI opens once, when you open it 1st time and then never again, no matter how often you click the app icon.

### The Workaround
Kill the WireGuard process, then click the app icon and voilà the GUI pops up again.

This is exactly what the OpenWireGuard app does: It kills the WireGuard task and launches the WireGuard client again.

### Install
Launch the DMG and drag the app to your applications-folder. Then use OpenWireGuard instead of the original app.
Do not delete the original app.

Drop me a star, if you like it :)
