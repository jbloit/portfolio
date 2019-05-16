# portfolio
portfolio static website. For working on layout only.


## layout with html and scss 
scss allows to work with structured css.
install sass, and setup watch to preprocess scss into css files.

```bash
cd css
sass --watch style.scss:style.css
```


### Resizing images
Fix width and preserve ratio
```bash 
for fff in `ls *.jpg`; do convert $fff -resize 1024x smaller/$fff; done
```


### Links
- [CSS guru Jen Simmons](https://labs.jensimmons.com/)
- [Gatsby images in portfolio](https://medium.freecodecamp.org/how-i-made-my-portfolio-website-blazing-fast-with-gatsby-82ccddc2f671)
- [css clip path utility](https://bennettfeely.com/clippy/)
