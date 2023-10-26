## Dot Slash Dash

### Solution

Download `morses.zip`, extract the file you will get `morses.wav`.

Upload to [Morse Code Adaptive Audio Decoder](https://morsecode.world/international/decoder/audio-decoder-adaptive.html), and click play.

![image](https://github.com/0hanif0/rAKSASA2023CTF-Writeups/assets/23289982/8456725b-3f7b-47eb-bfd7-d8c209d7d5f8)

Given text: `WELCOME TO WSCTF2021 . HERE IS THE DOWNLOAD LINK https://controlc.com/624ec7b2 . THE PASWORD TO SEE THE CONTENT IS WSCTF2021`.

Go to the given link using the given password, you will get the google drive link, download the zip file.

Open kali linux to crack the zip file using this cmd `fcrackzip -u -D -p rockyou.txt flag.zip`.

![image](https://github.com/0hanif0/rAKSASA2023CTF-Writeups/assets/23289982/19693f5a-073e-4f09-8e43-b3a2860b8037)

Extract the zip file using cracked password, You will get Base 32.

![image](https://github.com/0hanif0/rAKSASA2023CTF-Writeups/assets/23289982/356dbf60-d199-40fd-804e-84f347d133c4)

Just decode using this [Base32](https://cryptii.com/pipes/base32)

![image](https://github.com/0hanif0/rAKSASA2023CTF-Writeups/assets/23289982/3e56e596-43ff-4ed0-bbe3-1cc6ef1a6450)

### Flag

WSCTF{M0RSE_C0DE_G0ES_TUNUNU}
