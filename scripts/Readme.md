# Installation guide for running the IPS VPS script
    # Step 1
```    
wget -q https://github.com/ipsum-network/guides/blob/master/scripts/ipsum_setup.sh

```

    # Step 2
```
bash ips_install.sh

```
    # Step 3

```
watch ips-cli getinfo

```

    # Step 4
```    
apt install upstart

```
    # Step 5
```    
systemctl start Ips

systemctl status Ips

```
