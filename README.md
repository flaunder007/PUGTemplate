# PUGTemplate
Template for creation pages layouts with PUG, Sass and BEMTO PUG module

The project was created for PHPStorm and his file watchers.
```
Not include npm modules or else.
```
### File watcher for PUG on windows:

<p align="center">
  <img width="460" height="300" src="http://dl3.joxi.net/drive/2018/02/03/0006/3345/417041/41/81152f3f34.jpg">
</p>

```
Program:    C:\Users\Elijah\AppData\Roaming\npm\pug.md
Arguments:  $FileName$ --pretty
Output:     $FileNameWithoutExtension$.html
```
Argument "--pretty" will make your finally html code nicier and more readable.

### For Sass:

<p align="center">
  <img width="460" height="300" src="http://dl4.joxi.net/drive/2018/02/03/0006/3345/417041/41/b7779c00d3.jpg">
</p>

```
Program:    C:\Ruby22-x64\bin\sass.bat
Arguments:  --no-cache --update $FileName$:$FileNameWithoutExtension$.css --style compact
Output:     $FileNameWithoutExtension$.css:$FileNameWithoutExtension$.css.map
```
Argument "--style compact" make your css file compact, but unless than "--style compressed" it still will be readable.

Links:

- [PUG](https://pugjs.org/api/getting-started.html)  documentation
- [Sass](https://sass-lang.com/documentation/file.SASS_REFERENCE.html) - Sass documentation
