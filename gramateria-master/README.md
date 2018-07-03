# gramateria
A drag and drop web builder with materialize design.  
https://www.gramateria.com

Grapesjs + Materialize = 🔥

[Try Gramateria dashboard (Beta)](https://app.gramateria.com "Example on codepen.io")


### Version 1.0.5

- Add more sections ( Blog, Members, Grids )
- Change two code viewers into one
- Change Design and Icons
- Clear CSS codes for components
- Start Gramateria dashboard (Beta)
- Add copy HTML/CSS button in editor


### Version 1.0.4
 
- Load/save template file
- Change grapesjs/electron versions
- Add menus in desktop app
- Fix copy and paste error in desktop app
- Prompt to model popup


### Version 1.0.3

- Form elements
- Import HTML/CSS
- Auto save
- Dropdown navbar


### Building a desktop app.

`Note: You can use Gramateria by opening index.html file with Chrome browser and it works exactly the same as Desktop app.` 

----

```npm install```

```npm start```

##### Mac
```npm run build:mac```
##### Win
```npm run build:win```
##### Linux
```npm run build:lin```


### Include gramateria in your page 

###### 1 - Add grapesjs in head tag
```
<!-- grapesjs -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/grapesjs/0.14.6/css/grapes.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/grapesjs/0.14.6/grapes.min.js"></script>
<script src="https://cdn.rawgit.com/artf/grapesjs-plugin-export/master/dist/grapesjs-plugin-export.min.js"></script>

```
###### 2 - Add gramateria at the bottom of the page ( before ```</body>``` tag )
```
<!-- gramateria -->
<link rel="stylesheet" href="https://cdn.rawgit.com/ronaldaug/gramateria/master/dist/gramateria/gram.min.css">
<script src="https://cdn.rawgit.com/ronaldaug/gramateria/master/dist/gramateria/gram.min.js"></script>
```

###### 3 - Add example HTML into body tag
```
<div id="gjs">
 <div class="row">
    <div class="col m12">
    <h1>Hello world!</h1>
    <br/>
    <a href="https://www.gramateria.com" class="link">www.gramateria.com</a>
    </div>
</div>
<style></style>
</div>
```

###### [Example on codepen.io](https://codepen.io/ronaldaug/pen/yKPzWP "Example on codepen.io")


### Credit goes to 
- Grapesjs [Grapes JS](http://www.grapesjs.com/ "Grapes Js")
- Materialize [Materialize](http://www.materializecss.com/ "Materialize")
- Electron [Electron JS](http://www.electronjs.org/ "Electron Js")

Show your support by 🌟 the project, thanks.
