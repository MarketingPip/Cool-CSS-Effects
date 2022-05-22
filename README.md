# Cool-CSS-Effects

**Zoom In & Out**

```css
@keyframes ZoomInAndOut { 
  to { transform: scale(0.0); } 
}

p {
  position: relative;
  top: 100px;
  
  font: italic bold 5em/1 Bodoni, serif;
  color: #555;
  text-align: center;
  
  animation: ZoomInAndOut 5s infinite alternate;
}
```

```html
<p>Cool Bouncy Text </p>
```




---


**Falling Element**

```css


@keyframes Falling { 
  to { transform: scale(0.0); } 
}



.square{
    background-color: #e4708a;
  width: 100vw;
  height: 100vh;
  animation: Falling 2.4s infinite;
}


p {
  position: relative;
  top: 100px;
  font:  bold 10em/1 Bodoni, serif;
  color: white;
  text-align: center;
  

}
```



 ```html
 <div class="square">
    <p>I feel like I am falling</p>
  </div>
```
