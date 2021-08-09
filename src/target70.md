![image](https://user-images.githubusercontent.com/67518620/128775852-6fa0f020-80e5-45fc-bfbd-1877bed24559.png)


First 100% match?? O_o


```html
<div id="main-face"></div>

<style>
  body {
    background: #293462;
  }
  
  #main-face {
    height: 100px;
    width: 150px;
    background: radial-gradient(circle at 50% -130px, #FE5F55 200px, #A64942 200px);
    position: absolute;
    top: 110px;
    left: 125px;
    border-radius: 100px;
  }
  
  #main-face:before {
    position: absolute;
    content: '';
    background: #293462;
    width: 10px;
    height: 10px;
    border-radius: 50px;
    border: 10px solid #FFF1C1;
    box-shadow: 0px 0px 0px 10px #FE5F55;
    top: -15px;
    left: 25px;
    -webkit-box-reflect: right 40px;
  }
  
  #main-face:after {
    position: absolute;
    content: '';
    background: #293462;
    height: 10px;
    width: 10px;
    top: 50px;
    left: 60px;
    border-radius: 50%;
    -webkit-box-reflect: right 10px;
  }
  
</style>
```
