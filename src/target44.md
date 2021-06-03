![image](https://user-images.githubusercontent.com/67518620/120714259-f635fc80-c490-11eb-8f4c-1fc6d780b550.png)

```html
<!DOCTYPE>
<html>
  
<div class="main-block">
  <div class="circle green left"></div>
  <div class="circle green right"></div>
</div>


<style>
  body {
    background: #1A4341;
  }
  .green {
    background: #1A4341;
  }
  .main-block {
    height: 180px;
    width: 155px;
    margin: auto;
    margin-top: 60px;
    background: repeating-linear-gradient(
      #F3AC3C,
      #F3AC3C 20px,
      #1A4341 0.0001px,
      #1A4341 40px
    );
  }
  .circle {
    display: block;
    height: 210px;
    width: 160px;
    border-radius: 60px / 120px;
  }
  .circle.green.left {
    transform: translateX(-135px) translateY(-15px);
  }
  .circle.green.right {
    transform: translateX(130px) translateY(-225px);
  }
</style>
  
  
</html>

```
