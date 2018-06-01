# Installation guide for running the IPS VPS script
# Step 1
```    
wget -q https://raw.githubusercontent.com/MotoAcidic/guides/master/scripts/ipsum_setup.sh

```
# Step 2
```
chmod +x ipsum_setup.sh

```
# Step 3

```
./ipsum_setup.sh install

```
# Step 4

```
watch ips-cli getinfo

```

# Step 5
```    
apt install upstart

```
# Step 6
```    
systemctl start Ips

systemctl status Ips

```
