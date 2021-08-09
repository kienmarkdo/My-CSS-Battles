![image](https://user-images.githubusercontent.com/67518620/128782305-0d8dff7f-eb96-4bec-bd82-e497d9c055b7.png)



```html
<div id="square-yellow"></div>
<div id="square-green"></div>
<div id="square-dirty-yellow"></div>
<div id="dark-green-rectangle-1"></div>
<div id="dark-green-rectangle-2"></div>

<style>
  body {
    background: #0B2429;
  }
  
  #square-yellow {
    background: #F3AC3C;
    position: absolute;
    height: 100px;
    width: 100px;
    top: 135px;
    left: 150px;
    transform: rotate(45deg);
    z-index:1;
  }
  
  #square-dirty-yellow {
    background: #998235;
    position: absolute;
    height: 140px;
    width: 71px;
    top: 45px;
    left: 130px;
  }
  
  #square-green {
    background: #1A4341;
    position: absolute;
    height: 140px;
    width: 71px;
    top: 45px;
    left: 200px;
  }
  
  #dark-green-rectangle-1 {
    background: #0B2429;
    position: absolute;
    height: 140px;
    width: 70px;
    top: -10px;
    left: 230px;
    transform: rotate(-45deg);
  }
  
   #dark-green-rectangle-2 {
    background: #0B2429;
    position: absolute;
    height: 140px;
    width: 70px;
    top: -10px;
    left: 100px;
    transform: rotate(45deg);
  }
  
</style>

```
