## Exercise 1.4 

### Used commands:

#### In the terminal to run Ubuntu:
```
sudo docker run -it ubuntu
```

#### In the container:
```
apt-get update
apt-get -y install curl
sh -c 'while true; do echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website; done'

```
#### Output for "helsinki.fi"

![kuva](https://github.com/erjavaskivuori/devops-with-docker/blob/main/part1/exercise4-output.png)
