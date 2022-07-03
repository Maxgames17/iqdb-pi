changed a couple of things to build the docker image for my pi4

```bash
# build the image and set version as arm64
sudo docker build -f iqdb/Dockerfile -t evazion/iqdb:arm64 iqdb/
```
in docker-compose set the image field as such

```
image: evazion/iqdb:arm64
```
