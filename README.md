# slides-theme

Collection of personal `.scss` files that can be used to customize slides. To use, simply use the following code:

```
download.file(
  url = "https://raw.githubusercontent.com/thomvolker/slides-theme/main/[[THEME-NAME]]/[[THEME-NAME]].scss",
  destfile = "THEME-NAME.scss"
)
```

Subsequently, set the following in the `.yaml` file.

```
format:
  revealjs:
    theme: THEME-NAME.scss
    logo: "https://github.com/thomvolker/slides-theme/blob/main/universiteit-utrecht-logo.png?raw=true"
    incremental: false
```