## More Than Duck

### Solution

Download `duck4-s.jpg`.

Using stegseek in kali linux to see hidden data, you will get zip file `flag.zip` with password protected.

![image](https://github.com/0hanif0/rAKSASA2023CTF-Writeups/assets/23289982/dc37f618-77e7-43a5-b0b6-e222d89ce809)

After that, check the metadata for the picture using exiftool, you will get the interesting strings `flappybird`.

![image](https://github.com/0hanif0/rAKSASA2023CTF-Writeups/assets/23289982/7557780a-63f0-44ee-97f3-35f2c6c69514)

Extract the zip file using this password `flappybird`, you will get `flag.txt`.

![image](https://github.com/0hanif0/rAKSASA2023CTF-Writeups/assets/23289982/ca8b4fd5-0777-4271-b7ce-8520710031a0)

### Flag

`Is it a plane... is it a bird... it's cyber duck`
