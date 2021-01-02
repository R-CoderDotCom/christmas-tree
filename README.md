# Base R Christmas tree
A function to create a Christmas tree plot with base R.

**Note**: as the code uses emojis as pch symbols (the snow and the star) I recommend you to copy the function directly into the console instead of opening it with a script.

```r
chtree()
```
<p align="center">
  <img src = "https://user-images.githubusercontent.com/67192157/103097081-61d48d80-4606-11eb-8f97-49657bf3b361.png" alt = "Christmas tree in R">
</p>

## Change background color
```r
chtree(bg.col = "lightblue1")
```
<p align="center">
  <img src = "https://user-images.githubusercontent.com/67192157/103097116-7fa1f280-4606-11eb-836e-673fea053c3f.png" alt = "Xmas tree in R">
</p>

## Remove snow

```r
chtree(snow = FALSE)
```

<p align="center">
  <img src = "https://user-images.githubusercontent.com/67192157/103097150-a102de80-4606-11eb-96dd-2f11a0d1f297.png" alt = "R Christmas tree">
</p>


## Remove bulbs

```r
chtree(bulbs = FALSE)
```

<p align="center">
  <img src = "https://user-images.githubusercontent.com/67192157/103097269-0e167400-4607-11eb-9b5b-6b45ec6a6ea4.png" alt = "Arbol de Navidad en R">
</p>

## Remove star

```r
chtree(star = FALSE)
```

<p align="center">
  <img src = "https://user-images.githubusercontent.com/67192157/103100897-27262180-4615-11eb-964e-191481708e2e.png" alt = "R Christmas tree">
</p>


## Acknowledgements

The code is based on a [tweet by @jurbane2](https://twitter.com/jurbane2/status/1073648454981828608?s=03).
