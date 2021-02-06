## rpi-zalenium-docker

Customized dockerfile and supporting files to port Zalenium to Raspberry Pi3/4 platform (armhf)

This port is based on the great work based on the zolando/zalenium project -> https://github.com/zalando/zalenium


This project is also depandant on https://github.com/elgalu/docker-selenium (also , from same creators) which also needs to ported to RPI platform.

Both are attmepted in this repo. Although UNTESTED, WIP

## Instruction to build the image

Navigate to zalenium/docker folder

```
docker build -t sunnyd/zalenium .
```

Navigate to docker-selenium folder
First clone the https://github.com/elgalu/docker-selenium repo and just replace the Dockerfile with the one found in this repo in root
Then build using
```
docker build -t elgalu/selenium .
```
## Documentation

Check the complete documentation at https://zalando.github.io/zalenium/


