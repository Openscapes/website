# Amazing Website
Code for openscapes.org 
At Openscapes, we champion open practices in environmental science to help uncover data-driven solutions faster


# Notes to self:

```
## setup
library(blogdown)
blogdown::install_hugo()
blogdown::update_hugo()

## theme
blogdown::new_site(theme = "devcows/hugo-universal-theme")

## serve site! (also in the addins):
blogdown::serve_site()
```

How to include a redirect: 

Go to `/content/_redirects` and add for example: 

`/summit2019/ http://openscapes.github.io/summit2019`

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
