
# Using Motion css
![Ting Logo](/img/logo.png)
*  First step is to import  the css file from the cloned  folder
```html 
<html>
  <head>
    <title>
      MotionCss by okechukwu omeh 
    </title>
    <link rel="stylesheet" href="motion-css.css">
  </head>
      
</html>

```
* Second Step is to add it to your elements. The second class refers to the animation desired.
There are so many choices, but select the ones that apply to the icon choosen.
```html 
<div class="battery-icon charging">
   
</div>
```

## CSS Categories
* icons
* loading animations
* Ui Components


# Ui Components
 *  Buttons
     * This line of html code helps to render a gradient button.
     There are numerous buttons to pick from, and more will be added regularly.
 ```html

  
    <button class="roundBtn roundBtn-black">Motion</button>
    
 ``` 
 * The available buttons are
    
  ```html
      
        
          
<div class="pd-2">
    <h2>small corner Buttons</h2>
    <span class="btn btn-black">Motion</span>
    <span class="btn btn-yell">Motion</span>
    <span class="btn btn-gr">Motion</span>
    <span class="btn btn-red">Motion</span>
    <span class="btn btn-orange">Motion</span>
    <span class="btn btn-blue">Motion</span>
</div>
<div class="pd-2">
    <h2>small corner Buttons inverted</h2>
    <span class="btn btn-r-black">Motion</span>
    <span class="btn btn-r-yell">Motion</span>
    <span class="btn btn-r-gr">Motion</span>
    <span class="btn btn-r-red">Motion</span>
    <span class="btn btn-r-orange">Motion</span>
    <span class="btn btn-r-blue">Motion</span>
</div>
<div class="pd-2">
    <h2>Buttons Round corners</h2>
    <span class="roundBtn roundBtn-black">Motion</span>
    <span class="roundBtn roundBtn-yell">Motion</span>
    <span class="roundBtn roundBtn-gr">Motion</span>
    <span class="roundBtn roundBtn-red">Motion</span>
    <span class="roundBtn roundBtn-orange">Motion</span>
    <span class="roundBtn roundBtn-blue">Motion</span>
</div>
<div class="pd-2">
    <h2>Buttons Round corners inverted</h2>
    <span class="roundBtn roundBtn-r-black">Motion</span>
    <span class="roundBtn roundBtn-r-yell">Motion</span>
    <span class="roundBtn roundBtn-r-gr">Motion</span>
    <span class="roundBtn roundBtn-r-red">Motion</span>
    <span class="roundBtn roundBtn-r-orange">Motion</span>
    <span class="roundBtn roundBtn-r-blue">Motion</span>
</div>
<div class="pd-2">
    <h2>Gradient Buttons Round corners</h2>
    <span class="grdBtn grdBtn-bl-gr">Motion</span>
    <span class="grdBtn grdBtn-rd-bc">Motion</span>
    <span class="grdBtn grdBtn-or-bl">Motion</span>
    <span class="grdBtn grdBtn-rd-bl">Motion</span>
    <span class="grdBtn grdBtn-or-rd">Motion</span>
    <span class="grdBtn grdBtn-or-gr">Motion</span>


    <span class="grdBtn grdBtn-yell-gr">Motion</span>
    <span class="grdBtn grdBtn-or-gr">Motion</span>
</div>
 ```
![buttons img](/img/motion4.png)
          

*  Elements
   * Also there are many animated ui elements to pick from. From checkboxes to radio buttons
   * The colors can be changed by targeting the color of the element
 ```html

   <input id="checkBox" type="checkbox" class="checkbox">
           <label for="checkBox" class="checker">
               <div class="checkerIcon">
                   &nbsp;
               </div>
           </label>
```

![Elements img](/img/motion3.png)

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
![icons img](/img/motion2.png)

* load elements

![loading Logo](/img/motion1.png)

### Note: Motion Css is free and subject to your customization.

