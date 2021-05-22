![image](https://user-images.githubusercontent.com/67518620/119241364-d400be00-bb23-11eb-9a4c-402bd785ed63.png)



```html
<!DOCTYPE html>
<html>
<body style="background: #191919;">
  <div class="blue-line" id="top-rectangle"></div>
  <div class="blue-line" id="middle-rectangle"></div>
  <div class="blue-line" id="top-half-triangle-left"></div>
  <div class="blue-line" id="top-half-triangle-right"></div>
  <div class="blue-line" id="bottom-half-triangle-left"></div>
  <div class="blue-line" id="bottom-half-triangle-right"></div>
  <div class="blue-line" id="vertical-middle"></div>
  <div class="blue-line" id="long-bottom"></div>
  <div class="blue-line" id="short-bottom"></div>

<style>
  .blue-line {
    background: #5DBCF9;
    position: absolute;
    height: 9.5px;
    width: 110px;
  }
  #top-rectangle {
    background: transparent;
    height: 20px;
    width: 30px;
    border: 10px solid #5DBCF9;
    border-bottom: transparent;
    transform: translate(167px, 58px);
  }
  #middle-rectangle {
    background: transparent;
    height: 50px;
    width: 80px;
    border: 10px solid #5DBCF9;
    border-bottom: transparent;
    transform: translate(142px, 88px);
  }
  #top-half-triangle-left {
    height: 90px;
    width: 9.5px;
    transform: translate(151px, 98px) rotate(60deg);
  }
  #top-half-triangle-right {
    height: 90px;
    width: 9.5px;
    transform: translate(224px, 98px) rotate(-60deg);
  }
  #bottom-half-triangle-left {
    height: 9.5px;
    width: 29px;
    transform: translate(113px, 169px) rotate(55deg) skew(-35deg);
  }
  #bottom-half-triangle-right {
    height: 9.5px;
    width: 29px;
    transform: translate(243px, 169px) rotate(-55deg) skew(35deg);
  }
  #vertical-middle {
    height: 60px;
    width: 9.5px;
    transform: translate(187px, 125px);
  }
  #long-bottom {
    transform: translate(92px, 196px);
    width: 200px;
  }
  #short-bottom {
    transform: translate(137px, 216px);
  }
  
</style>
</body>
</html>


```
