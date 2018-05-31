# Installation guide for running the IPS VPS script
# Step 1
```    
wget -q https://raw.githubusercontent.com/ipsum-network/guides/master/scripts/ipsum_setup.sh

```
# Step 2
```
chmod +x ipsum_setup.sh
chmod +x ./ipsum_setup.sh install

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
