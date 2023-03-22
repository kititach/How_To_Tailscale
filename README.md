# How_To_Install_Tailscale

## Install : Tutorial https://tailscale.com/kb/1017/install/
```
sudo apt-get update
curl -fsSL https://tailscale.com/install.sh | sh
```

```
sudo tailscale up
```

## Login URL
![2023-03-20_16-10-10](https://user-images.githubusercontent.com/48780839/226294716-b8866a68-ab92-4bfe-a939-d6f369fd8fed.png)


## Subnet router failover
```
sudo tailscale up --advertise-routes=10.0.0.0/24
```
