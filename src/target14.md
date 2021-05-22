![image](https://user-images.githubusercontent.com/67518620/119214690-9efa5a00-ba96-11eb-88b1-5ec8ee23d380.png)

```html
<!DOCTYPE html>
<html>
<body style="background: #F2F2B6;">
  <section class="left-triangles">
    <div id="front-triangle"></div>
    <div id="back-triangle"></div>
  </section>
  <section class="right-triangles">
    <div id="front-triangle"></div>
    <div id="back-triangle"></div>
  </section>
</body>

<style>
  #front-triangle {
    width: 0px;
    height: 0px;
    z-index: 1;
    position: absolute;
  }
  #back-triangle {
    width: 0px;
    height: 0px;
    z-index: 0;
    position: absolute;
  }
  .left-triangles #front-triangle {
    border-left: 80px solid transparent;
    border-right: 80px solid transparent;
    border-top: 130px solid #FF6D00;
    margin-left: 50px;
    margin-top: 77px;
  }
  .left-triangles #back-triangle {
    border-left: 80px solid transparent;
    border-right: 80px solid transparent;
    border-top: 130px solid #FD4602;
    margin-left: 70px;
    margin-top: 77px;
  }
  .right-triangles #front-triangle {
    border-left: 80px solid transparent;
    border-right: 80px solid transparent;
    border-bottom: 130px solid #FD4602;
    margin-left: 165px;
    margin-top: 77px;
  }
  .right-triangles #back-triangle {
    border-left: 80px solid transparent;
    border-right: 80px solid transparent;
    border-bottom: 130px solid #FF6D00;
    margin-left: 185px;
    margin-top: 77px;
  }
</style>
<html>
  ```
