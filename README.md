
# Using Motion css
![Ting Logo](/img/logo.png)
*  First step is to import  the css file from the cloned  folder
```html 
<html>
  <head>
    <title>
      MotionCss by okechukwu omeh 
    </title>
    <link rel="stylesheet" href="motion-css.min.css">
  </head>
      
</html>

```
* Second Step is to add it to your elements the second class refers to the animation desired.
There are so many choices, but select the ones that apply to the icon choosen.
```html 
<div class="battery-icon charging">
   
</div>
```

## CSS Categories
* icons
* loading animations
* Ui Components

##  Adding loader animations to your Site
* Firstly, the html markup
```html
  <div class="center">
      <div class="circle-loading"></div>
  </div>
```
* Add a css element to hold your loader and another to toggle it
```css

.center{
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
  width: 100vw;
  height: 100vh;
  background-color: #9bf8e6;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  z-index: 99;

}
 .hidden{
  animation: fadeout 10s ;
  animation-fill-mode: forwards;
}
```
* Center and hidden was used in this demo
* To add this to your html pages You will Write just three lines of code at most. 

```javascript

   window.addEventListener('load', function(){
              document.querySelector(".center").classList.add('hidden');
          })

```

### Note: Motion Css is free and subject to your customization.

