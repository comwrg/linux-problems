# linux-problems
## -bash: warning: setlocale: LC_ALL: cannot change locale (en_US.UTF-8)
https://unix.stackexchange.com/questions/269159/problem-of-cant-set-locale-make-sure-lc-and-lang-are-correct/269160?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa

## change init level
https://itbilu.com/linux/management/4JEzjDV8G.html

## set service start level
https://askubuntu.com/questions/3913/start-ssh-server-on-boot

## change timezone
https://www.sysgeek.cn/change-timezone-linux/

## shadowsocks start on boot
自带 在目录/lib/systemd/system

## gpg public key delete by mistake
error message
```The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 7638D0442B90D010 NO_PUBKEY 04EE7237B7D453EC NO_PUBKEY EF0F382A1A7B6500```

apt-key adv --keyserver keyserver.ubuntu.com --recv-keys EF0F382A1A7B6500
