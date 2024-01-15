```
docker build . -t ansible
```
```
docker run -it --rm -v ${HOME}:/root/ -v ${PWD}:/work -w /work --net host ansible sh
```