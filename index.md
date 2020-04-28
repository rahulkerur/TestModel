<html>
  <head>
  <script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
  <script src="https://jeromeetienne.github.io/AR.js/aframe/build/aframe-ar.js"></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
  </head>
 		<body style=’margin : 0px; overflow: hidden;’>
  <a-scene embedded arjs=’sourceType: webcam;’>
      <a-marker preset=’hiro’>
        <!-- Adding an OBJ file to an AR Project-->
        <a-entity 
            obj-model=”obj: url(/path/to/nameOfFile.obj); 
            mtl: url(/path/to/nameOfFile.mtl)”>
        </a-entity>
              
      </a-marker>
  <a-entity camera>
  </a-entity>

      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
      <a-entity
          gltf-model="https://arjs-cors-proxy.herokuapp.com/https://raw.githack.com/AR-js-org/AR.js/master/aframe/examples/image-tracking/nft/trex/scene.gltf"
              scale="5 5 5"
              position="0 1 -250">
          </a-entity>
    </a-scene>
  </body>
</html>
