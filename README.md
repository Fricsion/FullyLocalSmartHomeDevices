# List of Fully Local Smart Home Devices

This repository aims to create a list of smart home devices that work locally (without internet connection/account) in any steps of the usage e.g. during setup process, when turned on and when operating. 

There should be a dedicated VLAN for smart devices. 

<img width="942" height="53" alt="Screenshot 2026-01-07 at 0 04 48" src="https://github.com/user-attachments/assets/b7590b99-afc5-47ad-8518-062a1d1fb318" />

If your setup is similar to mine, maybe we can help each other build this list!

Feel free to create a PR if you know such products with great support for without-internet usage. 

Inspired by awesome-selfhosted repo. 

## Qualification
Ask 5 questions:
- Does it NOT require internet connection when setting it up?
- Does it NOT require internet account when setting it up or using it?
- Does it NOT require internet when the device itself restarts either intentionally or by accident?
- Does it NOT require internet when Home Assistant instance restarts (e.g. upgrading the server)?
- Does it NOT require internet when it operates?

## Devices

### Plugs
#### Tapo 110M

- No internet setup: Home Assistant Matter Integration
- No internet turn on: It stays connected after reboot of both Home Assistant and the device itself.
- No internet operation: Fully operational with no internet connectivity.
- Additional Info: It can do power monitoring with Matter; Do not use TP-Link Integration on Home Assistant because it will require an account. 

