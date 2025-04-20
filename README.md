<!DOCTYPE html>
<html lang="en">
  <head>
    <script src="https://cdn.jsdelivr.net/npm/mind-ar@1.1.5/dist/mindar-image.prod.js"></script>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/mind-ar@1.1.5/dist/mindar-image-aframe.prod.js"></script>
  </head>

  <body>
    <a-scene
      mindar-image="imageTargetSrc:https://cdn.glitch.global/2b60304b-b88f-4fb9-b962-fddf642554cd/targets.mind?v=1745175771650;"
      vr-mode-ui="enabled: false"
      device-orientation-permission-ui="enabled: false"
    >
      <a-camera position="0 0 0" look-controls="enabled: false"></a-camera>
      <a-entity mindar-image-target="targetIndex: 0">
        <a-sphere position="0 0 0" radius="0.25" color="#EF2D5E"></a-sphere>
      </a-entity>
    </a-scene>
  </body>
</html>
