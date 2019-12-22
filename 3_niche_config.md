## Disable lid on xfce

I use xfce as desktop environment and have been annoyed by lid sensor issue in my macbook, so I disable the lid action according to this (link)[https://bbs.archlinux.org/viewtopic.php?id=195300].
Open `/etc/UPower/UPower.conf`

```
IgnoreLid=true
```

Also open `/etc/systemd/logind.conf`

```
HandlePowerKey=ignore
HandleSuspendKey=ignore
HandleHibernateKey=ignore
HandleLidSwitch=ignore
```

## Font config
