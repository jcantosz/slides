# Slides
Utility container for https://github.com/bketelsen/slides

Uses `/slides` as a working directory.

Automated build at https://hub.docker.com/r/jcantosz/slides

Build like:
```
docker build -t slides .
```

Run like:
```
docker run --rm -it jcantosz/slides
```

Build slides like:
```
docker run --rm -v $(pwd):/slides -it jcantosz/slides build
```

