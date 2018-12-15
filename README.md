# website
Code for openscapes.org

```
## setup
library(blogdown)
blogdown::install_hugo()
blogdown::update_hugo()

## theme
blogdown::new_site(theme = "devcows/hugo-universal-theme")
```

How to incorporate html into the config file: 

```
 logo_small = "img/logo-small.png"
    address = """<p><strong>Universal Ltd.</strong>
        <br>13/25 New Avenue
        <br>Newtown upon River
        <br>45Y 73J
        <br>England
        <br>
        <strong>Great Britain</strong>
      </p>
      """
```      