# lsblk
```
lsblk -o NAME,KNAME,STATE,SIZE
NAME            KNAME STATE    SIZE
fd0             fd0              4K
sda             sda   running   20G
├─sda1          sda1             1G
└─sda2          sda2            19G
  ├─centos-root dm-0  running   16G
  └─centos-swap dm-1  running    1G
sr0             sr0   running 1024M
```
