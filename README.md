# KAFKA-POC
A minimalistic ubuntu 20.04 Docker based project to use as a shell wrapper for your projects

## PREREQUISITES
Bash, make, docker. 

## USAGE
Check the usage
```bash
make
```
, which is the same as
```bash
make help
```

## INSTALL
Build the ubuntu 20.04 image, init the container and show the help from the deploy script
```bash
make install
```

## RUN 
Run an example function ... 
```bash
make run
```
## SPAWN !!!
To spawn this whole thingy into YOUR thingy do:
```bash
cp -r ~/opt/kafka-poc ~/opt/thingy
export to_srch=kafka-poc
export to_repl=thingy
export dir_to_morph=~/opt/thingy
docker exec -it proj-devops-con ./deploy -a do_morph_dir
```
