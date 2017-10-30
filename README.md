# Royal 👑

Royal is an extremely lightweight scss framework for people who regularly write SCSS code and want to import files modularly.

### Curl Initialize
Add the _initialize.scss to your sass directory. Use this file to store all of your import mappings and then add to it with any of the following Curl commands.
```
curl https://raw.githubusercontent.com/ScottyVG/Royal/master/src/_initialize.scss >> _initialize.scss
```

### Curl Buttons
Add the _buttons.scss to your sass directory and import _buttons.scss file into your _initialize.scss file
```
curl https://raw.githubusercontent.com/ScottyVG/Royal/master/src/_buttons.scss >> _buttons.scss && echo "@import \"buttons\";" >> _initialize.scss
```

### Curl Flex-Box
Add the _flex-box.scss to your sass directory and import _flex-box.scss file into your _initialize.scss file
```
curl https://raw.githubusercontent.com/ScottyVG/Royal/master/src/_flex-box.scss >> _flex-box.scss && echo "@import \"flex-box\";" >> _initialize.scss
```

### Curl Grid
Add the _grid.scss to your sass directory and import _grid.scss file into your _initialize.scss file
```
curl https://raw.githubusercontent.com/ScottyVG/Royal/master/src/_grid.scss >> _grid.scss && echo "@import \"grid\";" >> _initialize.scss
```
