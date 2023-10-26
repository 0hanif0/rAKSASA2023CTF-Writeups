## AmongUSB

### Solution

Download `amongusb.zip`, and extract the file.

Using usbrip in kali linux, for installation can refer this [usbrip](https://github.com/snovvcrash/usbrip).

Using this cmd `sudo usbrip events violations auth.json -f admin_syslog`. actually this cmd is for search the event history of the external USB devices for violations based on the list of trusted USB devices `auth.json`.

![image](https://github.com/0hanif0/rAKSASA2023CTF-Writeups/assets/23289982/b1ae98e7-f2c4-4a87-9686-ab64ed4d3fa3)

After that decode the Serial Number from usbrip using [Base32](https://cryptii.com/pipes/base32).

![image](https://github.com/0hanif0/rAKSASA2023CTF-Writeups/assets/23289982/0dc325a0-72da-4eca-a644-6eb7e7a9e00a)

### Flag

`WSCTF2021{th3r3_1s_imp0stor_4m0ng_u5}`
