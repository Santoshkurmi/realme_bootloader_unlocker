
install this dependency for the script for debian.

```
apt-get install libwww-perl libcrypt-rijndael-perl
```


```
perl deeptesting-junk.pl pcb 0xHHHHHHHH imei DDDDDDDDDDDDDDD cmd applyLkUnlock
```
pcb 0xHHHHHHHH is a serial number of the phone in device info(zero x is compulsary above)
imei DDDD is a imei1 

If the answer is `{"resultCode":0,"msg":"SUCCESS"}`, its means form is submitted.
and after 1 or few minutes it will be accepted.to check if accepted or not

```
perl deeptesting-junk.pl pcb 0xHHHHHHHH imei DDDDDDDDDDDDDDD cmd checkApproveResult
```

after this if you get a long number of unlock code,its means its unlocked,just open the deep testing
app and unlock the bootloader.make sure you are in chinise rom.
## This script is not created by me.I have just changed the server to china and modified device model to support for chinese rom