# Task 1
### Resource help:
https://www.youtube.com/watch?v=gAkwW2tuIqE
https://docs.docker.com/
### Docker HUB repo
https://hub.docker.com/repository/docker/vineetahuja/baatcheet/general

I explored docker for first time and found such a great thing existed to share projects easily

# Task 2
Option 1 will be better as it saves my effort
we can do by creating a non-root access user and adding that user in dockergroup by:
1. Create the docker group
```
sudo groupadd docker
```
2. Add your user to the docker group.
```
sudo usermod -aG docker $USER
```

