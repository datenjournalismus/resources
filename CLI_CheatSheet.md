# CLI CheatSheet
##### curated by [@pushthings4ward](http://www.twitter.com/pushthings4ward)


### Random stuff

#####Encode and decode using Base64 representation (OSX)

```shell
$ base64 -i IMAGE_URL -o OUTPUT_FILE
```

#####How to run a script starting from a specific line

```shell
$ bash <(sed -n '5,$p' yourscript.sh)
```


#####How install imagemagick with homebrew

```shell
$ brew update && brew upgrade && brew install imagemagick
```