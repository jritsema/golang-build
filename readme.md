### golang-build

a golang build environment image that contains useful tools for xplat compilation and publishing to github

#### usage

```
$ docker run -it --rm -v $(pwd):/go/src/app jritsema/golang-build /go/src/app/build.sh
```