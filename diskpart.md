### Only ever needed...
Only ever needed to use DiskPart to increase or decrease a volume, or convert MBR disk to GPT.

## Convert GPT
```
cmd.exe > diskpart
DISKPART.exe > LIST DISK
DISKPART.exe > SEL DISK <disk-num>
DISKPART.exe > CLEAN
DISKPART.exe > CONVERT GPT
DISKPART.exe > SEL DISK 0
DISKPART.exe > CREATE PART PRIMARY
DISKPART.exe > exit
```

