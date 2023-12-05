# Import GPG keys

```
sudo pacman-key --recv-key 1BA91B820FEAB29A --keyserver keyserver.ubuntu.com 
```

# Locally sign imported GPG keys

```
sudo pacman-key --lsign-key 1BA91B820FEAB29A
```

# Add the repository:

```
sudo nano /etc/pacman.conf
```

# Add the following to the end of the file

```
[lcqt2]
Server = https://brandowlucas.github.io/lcqt2-Arch/
```

# Install lcqt2

```
sudo pacman -Sy lunar-client-qt2
```
