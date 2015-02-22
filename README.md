# Build
```cli
docker build -t velcrin/incubator .
```
# Run
```cli
docker run -vit `pwd`:/workspace -e USER=$USER -e USERID=$UID -p 3000:3000 -p 35729:35729 velcrin/incubator
```
