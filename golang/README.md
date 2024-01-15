```
docker build . -t golang
```
```
docker run -it --rm -v ${HOME}:/root/ -v ${PWD}:/work -w /work --net host golang sh
```