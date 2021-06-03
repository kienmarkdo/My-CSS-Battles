![image](https://user-images.githubusercontent.com/67518620/120597912-a107d580-c413-11eb-9c5c-40558d3a3cc9.png)

Used CSS flexbox for this challenge.

```html
<!DOCTYPE html>
<html>

<body class="vertical-container">
  <div class="v br">
    <div class="c br"></div>
    <div class="h br"></div>
  </div>
  <div class="v br">
    <div class="c br"></div>
  </div>
  <div class="v dr">
    <div class="c dr"></div>
    <div class="h s dr"></div>
  </div>
  <div class="v br">
    <div class="c br"></div>
    <div class="h s br"></div>
    <div class="h s br" id="second"></div>
  </div>
</body>

<style>
  body {
    background: #191919;
  }
  /* bright red */
  .br {
    background: #FE5F55;
  }
  /* dark red */
  .dr {
    background: #A64942;
  }
  
  .vertical-container {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    padding: 25px;
    transform: translateX(5px);
  }
  
  /* vertical lines */
  .v {
    height: 100px;
    width: 10px;
    border-bottom-right-radius: 230px;
  }
  
  /* circles */
  .c {
    width: 50px;
    height: 38px;
    border-radius: 50%;
    transform: translateX(-40px) translateY(70px);
  }
  
  /* horizontal lines */
  .h {
    height: 10px;
    width: 78.5px;
    transform: translateY(-48px);
  }
  
  /* horizontal short */
  .h.s {
    height: 10px;
    width: 40px;
  }
  /* second horizontal line on the right-most note */
  #second {
    margin-top: 10px;
  }
</style>

</html>
```
