# Requirements:
This codebase presumes a koffer bundle present in the `/tmp/` directory.
    
### 1. Aquire root & unpack tarball
```
sudo -i
```
```
tar -xv -C /root -f /tmp/koffer-bundle.*.tar
```
### 2. Run CloudCtl stand up script
```
 ./start-cloudctl.sh
```
### 3. Exec into CloudCtl
```
 podman exec -it cloudctl-one connect
```
### 4. Run p1 init script
```
 p1
```
# Demo:
  - Building the bundle    
![bundle](./web/bundle.svg)
