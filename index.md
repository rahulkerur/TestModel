<html>
  <script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
<script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar-nft.js"></script>
<body style=’margin : 0px; overflow: hidden;’>
  <a-scene embedded arjs=’sourceType: webcam;’>
      <a-marker preset=’hiro’>
	  	<a-box position="0 0 0" rotation="0 0 0" color="#4CC3D9"></a-box>
      </a-marker>
  <a-entity camera>
  </a-entity>
  </a-scene>
</body>
</html>
