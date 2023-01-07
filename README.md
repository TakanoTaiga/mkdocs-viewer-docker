# mkdocs-viewer-docker

## How to use
example Directory tree
```
example_documnet/
    ├ docs/
    ├ mkdocs.yml
```

example commands
```
cd ~/example_documnet
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs takanotaiga/mkdocs:latest
```
