# website
Code for openscapes.org


# Notes to self:

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

## Notes from Alison PH

(from RLadies Slack):

Some troubleshooting tips are to just use Netlify and drag and drop your public folder (built locally) to see if things render. You’ll want to move your images to `static/img/`. You currently have them all in `themes/hugo-universal-theme/static/img`.

If you want the full background image to rotate (rather than images over the background), you’ll need to edit the `carousel.html` widget, probably to rotate the `jumbotron` css class. That is about as far as I could get!
If you want to see a theme that has a hero carousel widget (so where the full image rotates), check out the academic theme: https://github.com/gcushen/hugo-academic/issues/622

This looks like a good tutorial for how to change how the owl javascript widget works: https://webdesign.tutsplus.com/tutorials/how-to-build-a-full-screen-responsive-carousel-slider-with-owljs--cms-31771