<template>
  <div class="hello">
  <div class="logo">
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" style="isolation:isolate" viewBox="0 0 560 315" width="560" height="315"><defs>
      <clipPath id="_clipPath_giMwdyZveTp3HSqVUMU348NOBOB9XTOg"><rect width="560" height="315"/></clipPath>
      </defs><g clip-path="url(#_clipPath_giMwdyZveTp3HSqVUMU348NOBOB9XTOg)">
        <polygon points="268.525,34.954,241.294,128,174.329,57.895"/>
        <polygon points="152.084,240.68,226.506,178.097,245.871,274.353"/>
        <polygon points="341.693,233.293,290.706,182.918,360.277,159.826"/>
        <polygon points="285.867,262.744,250.551,225.992,300.906,203.615"/>
        <polygon points="191.332,167.02,144.605,125.352,204.054,105.725"/>
        <polygon points="157.788,219.134,133.23,161.545,195.38,169.077"/>
        <polygon points="144.605,98.706,167.123,68.849,182.315,103.273"/>
        <polygon points="288.759,179.896,293.796,151.033,331.257,156.78"/>
        <polygon points="258.219,78.056,281.311,40.117,290.706,79.196"/>
        <polygon points="268.654,133.877,260.372,92.149,294.775,111.631"/>
        <polygon points="303.053,105.582,297.066,65.365,348.579,57.625"/>
        <polygon points="292.554,193.492,250.551,219.134,262.027,176.444"/>
        <polygon points="229.087,132.106,219.245,167.02,204.054,138.196"/>
        <polygon points="133.23,156.11,147.482,133.877,159.693,157.33"/>
        <polygon points="196.333,186.796,209.101,167.344,208.76,187.103"/>
        <polygon points="298.621,255.973,311.598,210.612,321.395,249.117"/>
        <polygon points="377.701,152.885,288.745,141.902,347.429,79.196"/></g></svg>
  </div>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  width: 100%;
  height: 100vh;
  background: white;
}
.logo{
      text-align: center;
    position: relative;
    right: 0;
    top: 30vh;
}
svg {
  height: 100%;
  fill: rgb(255, 122, 233);
    transition-duration: 1.25s;

}
svg:hover {
  transform: scale(1.15);
  transition-duration: 1.25s;
}

svg polygon{
    transition-duration: 1.15s;

}

svg:hover polygon:nth-child(1) {
  transform: translate(0px, -20px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(2) {
  transform: translate(0px, 20px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(3) {
  transform: translate(20px, 0px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(4) {
  transform: translate(0px, 20px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(5) {
  transform: translate(-10px, -20px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(6) {
  transform: translate(-10px, 0px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(7) {
  transform: translate(-5px, -20px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(8) {
  transform: translate(10px, -15px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(9) {
  transform: translate(0px, -20px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(10) {
  transform: translate(0px, -20px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(11) {
  transform: translate(0px, -20px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(12) {
  transform: translate(10px, 5px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(13) {
  transform: translate(-10px, -15px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(14) {
  transform: translate(-10px, -5px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(16) {
  transform: translate(15px, 15px);
    transition-duration: 1.15s;
}
svg:hover polygon:nth-child(17) {
  transform: translate(15px, -20px);
    transition-duration: 1.15s;
}



/* svg:hover polygon{
  /* transform: scale(1.55);
  transition-duration: 1s;} */

</style>
