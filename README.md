# Thor

Comandos de instalação da workstation Thor

O arquivo grafana.db conteḿ a configuração copiada das estações thor e cougar para o PCP

Sugestão para as partições:
```
[alberto@thor ~]$ df -h
Filesystem                         Size  Used Avail Use% Mounted on
devtmpfs                           4.0M     0  4.0M   0% /dev
tmpfs                               16G     0   16G   0% /dev/shm
tmpfs                              6.3G  1.7M  6.3G   1% /run
/dev/mapper/fedora_thor-root       246G   70G  163G  31% /
tmpfs                               16G     0   16G   0% /tmp
/dev/sda2                          488M  271M  181M  60% /boot
/dev/sda1                          200M  7.1M  193M   4% /boot/efi
/dev/mapper/fedora_thor_data-home  6.8T  203G  6.2T   4% /home
```

```
[alberto@cougar ~]$ df -h
Filesystem                     Size  Used Avail Use% Mounted on
devtmpfs                       4.0M     0  4.0M   0% /dev
tmpfs                           32G     0   32G   0% /dev/shm
tmpfs                           13G  2.0M   13G   1% /run
/dev/sda3                      433G   72G  339G  18% /
tmpfs                           32G     0   32G   0% /tmp
/dev/sda2                      974M  277M  630M  31% /boot
/dev/sda1                      511M  7.1M  504M   2% /boot/efi
/dev/mapper/storage--lvm-home  7.3T  341G  6.6T   5% /home
```
