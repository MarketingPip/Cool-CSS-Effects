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

**Bouncy Text**


```css
@keyframes BouncyText  {
  0% {
    transform: translateY(100%);
  }
  10% {
    transform: translateY(0%);
  }
  20% {
    transform: translateY(100%);
  }
 30% {
     transform: translateY(0%);
  }
   40% {
    transform: translateY(100%);
  }
   50% {
    transform: translateY(0%);
  }
  
   60% {
    transform: translateY(100%);
  }
    70% {
    transform: translateY(0%);
  }
   80% {
    transform: translateY(100%);
  }
   90% {
    transform: translateY(0%);
  }
  
   100% {
    transform: translateY(100%);
  }
}


p {
  position: relative;
  top: 100px;
  
  font: italic bold 5em/1 Bodoni, serif;
  color: #555;
  text-align: center;
  
  animation: BouncyText 5s infinite alternate;
}
```

**Color Changing Text**

```css
@keyframes ColorChangingText {
  0% {
    color: #e20d0d;
  }
  25% {
    color: #e20d0d;
  }
  50% {
    color: #f0d817;
  }
 75% {
    color: #3eb308;
  }
}

p {
  position: relative;
  top: 100px;
  
  font: bold 5em/1 Bodoni, serif;
  color: #e20d0d;
  text-align: center;
  
  animation: ColorChangingText 5s infinite alternate;
}
```



**Fade Out**

```css

@keyframes fadeOut  { 
  to { opacity: 0; } 
}

p {
  position: relative;
  top: 100px;
  
  font: italic bold 5em/1 Bodoni, serif;
  color: #555;
  text-align: center;
  
  animation: fadeOut 1s  ease-in-out 3s;
  animation-fill-mode: forwards;  
}

```
