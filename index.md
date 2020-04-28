<!DOCTYPE html>
<html>
  <head>
  <script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
      <a-scene>
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="0.5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
      <a-entity gltf-model="https://raw.githack.com/rahulkerur/testmodel/master/thesis-model.gltf"
       scale="0.0000000001 0.0000000001 0.0000000001"
       position="0 0 -250"
      	></a-entity>    
       <a-entity gltf-model="https://arjs-cors-proxy.herokuapp.com/https://raw.githack.com/AR-js-org/AR.js/master/aframe/examples/image-tracking/nft/trex/scene.gltf"
       scale="2 2 2"
       position="0 0 -250"
       	></a-entity> 
    </a-scene>
  </body>
</html>
