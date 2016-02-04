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


#####How to select the top 10 largest values from columns in R

```R
Var1 <- 90:115
Var2 <- 1:26
Var3 <- 52:27


data <- data.frame(Var1, Var2, Var3)

df.new <- data[sort(unique(c(sapply(data,order,decreasing=T)[1:10,]))),]
```