# notes
This is where I keep my notes

### system d services
```
journlctl -f -u <servicename> 
```
- `-f` follows the journal loging
- `-u` specifies service


```
systemctl status <servicename>
```
- gives status of service

```
sudo systemctl stop <servicename>
```
- guess what? It stops the service
- other commands:
  - start
  - enable
  - disable
