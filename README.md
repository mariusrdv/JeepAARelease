# Moved to google play store
I have released my app in google play store, but it is in early access(closed testing). To access app, you need just to join google group [jeepaa - Google Groups](https://groups.google.com/g/jeepaa). and then you should be able to access (same account email) https://play.google.com/store/apps/details?id=com.mariusrdv.jeepaa

# JeepAA(Jeep android auto)
JeepAA - intended for use with ELM327 bluetooth device + android device + Uconnect infotainment system (Panasonic manufacturer with android auto support).
Communication with OBD2 adapter implemented with "ObdMetrics" library - https://github.com/tzebrowski/ObdMetrics

- Tested only with Jeep Cherokee 2019 Limited, 2.0L turbo, ZF9 gearbox, Uconnect 8.4 (Should work and with other Cherokee KL 2018+ petrol engines)
- Bluetooth device: Vgate vLinker MC+ (should be ok and cheap ELM327 1.5)
- Android device: Xiaomi Note 10 pro (Android 13). App supports Android 9 and up.

Enable unknown sources
- Open Android Auto on phone
- Click hamburger icon at top left -> Settings
- Scroll to Version at bottom and tap ~10 times to unlock Developer Mode
- Click kebab icon at top right -> Developer settings
- Scroll to bottom and enable “Unknown sources”

How to install:
- Download latest app apk file from release section JeepAA-xxx-signed.apk (https://github.com/mariusrdv/JeepAARelease/releases)
- Copy to device
- Install app and run
* Grant bluetooth and location permissions
* Press "Enable android auto" button on bottom of the screen
- Select the same JeepAA-xxx-signed.apk (you just downloaded and copied to device storage)
* (Only first time run - On dialog press "Settings" -> enable "Allow from this source" -> enable "I'am aware of the possible risks....." -> wait 10 sec and "OK"
- Press Update
- Wait till app installs again
- You are ready to go

How to update new version:
- Copy to device new version apk
- Press "Enable android auto" button on bottom of the screen
- Select the same JeepAA-xxx-signed.apk (you just downloaded and copied to device storage)
- Press Update
- Wait till app installs again

|                                                     |                                                     |
|-----------------------------------------------------|-----------------------------------------------------|
| ![IMG_20231212_134506](https://github.com/mariusrdv/JeepAARelease/assets/1947733/4742800f-e283-46da-a4c3-e9e29213feb0) | ![IMG_20231212_134519](https://github.com/mariusrdv/JeepAARelease/assets/1947733/a683226f-ecac-4a3b-9688-86b819b8dfe8) |
| ![IMG_20231212_134553](https://github.com/mariusrdv/JeepAARelease/assets/1947733/57dee761-5838-4279-a21e-0afd506a9c12) | ![IMG_20231212_134607](https://github.com/mariusrdv/JeepAARelease/assets/1947733/f6d74029-c409-4655-b1db-746d67405b64) |
| ![IMG_20231212_134439](https://github.com/mariusrdv/JeepAARelease/assets/1947733/fa4dbc04-2742-49fe-94e6-529e7c8a75ed) | ![IMG_20231212_134456](https://github.com/mariusrdv/JeepAARelease/assets/1947733/5ee5c6d2-d4e5-4267-98c4-c4a8f4046290) |
| ![IMG_20231212_134439](https://github.com/mariusrdv/JeepAARelease/assets/1947733/ad2fd247-2266-4b51-a64a-21b0aed65a6e) |  |

