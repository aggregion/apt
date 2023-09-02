# Debian apt repo

On Ubuntu 20.04

```bash
echo 'deb [arch=amd64] https://aggregion.github.io/apt focal main' \
  | tee /etc/apt/sources.list.d/aggregion.list
wget -qO - https://aggregion.github.io/apt/public.key | apt-key add -
apt update
```
