![image](https://user-images.githubusercontent.com/67518620/119408654-10632400-bcb4-11eb-8e1d-eef036a1bcbb.png)


```html
<!DOCTYPE html>
<html>
<body style="background: #191919;">
  <!-- ======  HTML structure  ====== -->
  <div class="black-circle"></div>
  <div class="orange-rectangle"></div>
  <div class="orange-pupil"></div>
  <!-- nose -->
  <div id="nose"></div>
  <!-- left eye -->
  <div class="orange-rectangle" id="left-eye-border"></div>
  <div class="black-circle" id="left-iris"></div>
  <div class="orange-pupil" id="left-pupil"></div>
  <!-- right eye -->
  <div class="black-circle" id="circle-under-eye"></div>
  <div class="orange-rectangle" id="right-eye-border"></div>
  <div class="black-circle" id="right-iris"></div>
  <div class="orange-pupil" id="right-pupil"></div>
  
  <!-- ======  CSS style  ====== -->
  <style>
    /* define base characteristics for the classes */
    .black-circle {
      height: 90px;
      width: 90px;
      position: absolute;
      border-radius: 50%;
    }
    .orange-rectangle {
      height: 115px;
      width: 115px;
      position: absolute;
    }
    .orange-pupil {
      position: absolute;
      width: 10px;
      height: 5px; /* as the half of the width */
      border-top-left-radius: 100px;  /* #px of height + #px of border */
      border-top-right-radius: 100px; /* #px of height + #px of border */
    }
    
    /* left eye */
    #left-eye-border {
      background: #E08027;
      transform: translate(80px, 69px);
      border-top-right-radius: 50%;
      border-bottom-left-radius: 50%;
      border-bottom-right-radius: 50%;
    }
    #left-iris {
      background: #191919;
      transform: translate(92.5px, 81.5px);
    }
    #left-pupil {
      border: 10px solid #E08027;
      transform: translate(122px, 117px);
      border-bottom: 0;
    }
    /* right eye */
    #circle-under-eye {
      height: 135px;
      width: 135px;
      background: #191919;
      transform: translate(180px, 60px);
    }
    #right-eye-border {
      background: #E08027;
      transform: translate(190px, 69px);
      border-top-left-radius: 50%;
      border-bottom-left-radius: 50%;
      border-bottom-right-radius: 50%;
    }
    #right-iris {
      background: #191919;
      transform: translate(202.5px, 81.5px);
    }
    #right-pupil {
      border: 10px solid #E08027;
      transform: translate(232px, 117px);
      border-bottom: 0;
    }
    /* nose */
    #nose {
      position: absolute;
      height: 69px;
      width: 69px;
      background: #E08027;
      transform: translate(157px, 132px) rotate(-45deg);
    }
    
    
  </style>
</body>
<html>
  ```
