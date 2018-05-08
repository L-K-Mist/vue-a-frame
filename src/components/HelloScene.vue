<template>
<a-scene>
  <a-assets>
    <!-- <img id="sky" src="sky.jpg"> -->
    <a-asset-item id="map" src="static/edamame2.gltf"></a-asset-item>
  </a-assets>


  <!-- <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
  <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
  <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
  <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#43C877"></a-plane> -->
  <a-gltf-model src="#map" scale="0.5 0.4 0.5" rotation="4.64 -1.37 -4.52"></a-gltf-model>
  <a-sky color="#8ddfff"></a-sky>

<a-entity position="-24.774 20 27.349" rotation="-21.314029978866625 -33.80450991271857 20.110818609091893" look-controls="" wasd-controls="" camera="zoom:1.53;near:0.595;active:true;userHeight:1.6" data-aframe-inspector-original-camera=""></a-entity>

  <a-entity light="intensity:0.6;castShadow:false;type:hemisphere" position="1.551 29.815 -28.281" ></a-entity>
</a-scene>
</template>

<script>
import "aframe";
//import mapModel from "static/edamame2.gltf";

export default {
  name: "HelloScene",
  data: () => ({
    //map: mapModel
  })
};
</script>

<style>
.fullscreen {
  height: 100vh;
  position: relative;
}
</style>
