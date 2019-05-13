# portfolio
portfolio static website




### Resizing images
Fix width and preserve ratio
```bash 
for fff in `ls *.jpg`; do convert $fff -resize 1024x smaller/$fff; done
```