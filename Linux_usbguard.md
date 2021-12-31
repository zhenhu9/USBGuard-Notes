# usbguard

This App provides a command line interface to manage USB devices. Root and the members of wheel group can authorize usb devices by default.

The simple way to use it:

```
usbguard list-devices	/* list all devices which are allowed and blocked.
usbguard allow-device ID	/* Allow the blocked device ID in the list.
              -p, --permanent	/* Make the configuration persist.
```

------
