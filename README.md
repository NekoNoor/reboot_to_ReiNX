# Reboot to ReiNX

This is a very simple fork of https://github.com/Atmosphere-NX/Atmosphere/blob/master/troposphere/reboot_to_payload/

The only changes are:

- Read `sdmc:/ReiNX.bin` instead of `sdmc:/atmosphere/reboot_payload.bin`.
- Reboot immediately instead of requiring the user to press the [-] button.
