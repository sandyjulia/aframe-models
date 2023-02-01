# aframe-models
Hier finden Sie AFrame-Modelle
<!DOCTYPE html>
<html>
  <head>
    <script src="https://aframe.io/releases/1.1.0/aframe.min.js"></script>
    <script src="https://jeromeetienne.github.io/AR.js/aframe/build/aframe-ar.js">
    </script>
  </head>
  <body>
    <a-scene embedded arjs>
      <a-marker preset="hiro">
          <a-plane position="0 0 0" color="blue" height="5" width="5" rotation="-90 0 0" opacity="0.5"></a-plane>
      <a-plane position="2.5 2.5 0" color="green" height="5" width="5" rotation="0 -90 0" opacity="0.5"></a-plane>
      <a-plane position="-2.5 2.5 0" color= "red" height="5" width="5" rotation="0 -90 0" opacity="0.5"></a-plane>
      <a-plane position="0 5 0" color= "purple" height="5" width="5" rotation="-90 0 0" opacity="0.5"></a-plane>
      <a-plane position="0 2.5 -2.5" color= "yellow" height="5" width="5" rotation="0 0 -90" opacity="0.5"></a-plane>
      <a-plane position="0 2.5 2.5" color= "lightblue" height="5" width="5" rotation="0 0 -90" opacity="0.5"></a-plane>
      </a-marker>
      <a-camera position="0 0 0"> </a-camera>
    </a-scene>
  </body>
</html>
