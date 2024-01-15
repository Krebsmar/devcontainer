```
docker build . -t terraform
```
```
docker run -it --rm -v ${HOME}:/root/ -v ${PWD}:/work -w /work --net host terraform sh
```