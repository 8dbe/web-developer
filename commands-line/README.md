### Basics linux commands

```
cd ~    racine
pwd     where
ls      list
ls -a   hiden list(all)
cd      change D
cp      copy
cat     see 
echo    print 
top     services 

```
### docker on ubuntu 
uninstall any old Docker software
```
sudo apt-get remove docker docker-engine docker.io
```
To install Docker:
```
sudo apt install docker.io
```
The Docker service needs to be setup to run at startup.
```
sudo systemctl start docker
```
```
sudo systemctl enable docker
```
