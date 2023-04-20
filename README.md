<!DOCTYPE html>
<html>
  <head>
    <style>
      /* Set the position and dimensions of the element */
      #moving-element {
        position: absolute;
        width: 100px;
        height: 100px;
        background-color: blue;
      }

      /* Define the animation */
      @keyframes move {
        from { left: -100px; }
        to { left: 100%; }
      }

      /* Apply the animation to the element */
      #moving-element {
        animation-name: move;
        animation-duration: 5s;
        animation-iteration-count: infinite;
        animation-timing-function: linear;
      }
    </style>
  </head>
  <body>
    <div id="moving-element"></div>
  </body>
</html>
