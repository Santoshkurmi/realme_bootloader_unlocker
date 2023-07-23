
install this dependency for the script

```
apt-get install libwww-perl libcrypt-rijndael-perl
```
for debian.

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
