디스크 확인
```
lsblk
```

파티션 나누기 
```
fdisk /dev/nvme1n1
```

파일 시스템 포멧
```
mkfs.xfs /dev/nvme1n1p1
```
