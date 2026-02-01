# thumbsup :: slideshow generation

https://github.com/thumbsup/thumbsup

https://thumbsup.github.io/docs/

```bash
cd ~/github/campusiot/campusiot.github.io
mkdir images
docker run -v `pwd`:/work thumbsupgallery/thumbsup thumbsup \
    --input /work/photos \
    --output /work/images \
    --title 'CampusIot Gallery' \
    --footer '© CampusIoT, LIG, Université Grenoble Alpes - 2015-2026. <a href="credits.txt">Credits</a>'
cp photos/credits.txt images/
```

## TODO

* [ ] improve CSS of slideshow
* [ ] add comments on pictures
