# portfolio
portfolio static website


Roadmap: 
1-layout with html and scss 
2-integrate into gatsby, to get access to more plugins (multilingual for isntance) and data layer
3-refine UI from within gatsby

## layout with html and scss 
scss allows to work with structured css.
install sass, and setup watch to preprocess scss into css files.


### Resizing images
Fix width and preserve ratio
```bash 
for fff in `ls *.jpg`; do convert $fff -resize 1024x smaller/$fff; done
```


### Links

[Gatsby images in portfolio](https://medium.freecodecamp.org/how-i-made-my-portfolio-website-blazing-fast-with-gatsby-82ccddc2f671)