<template>
  <div id="landing">
    <!-- {{msg}} -->
      <h1>Jacob Kolodziej Music</h1>
  </div>
</template>

<script>
export default {
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    #landing {
        /* position: absolute;; */
        /* top: 0; */
        height: 100vh;
        width: 100vw;
        overflow: hidden;
        background-image: url('../assets/trumpet.jpg');
        background-size: cover; 
        background-attachment: fixed;
        display: flex;
        align-items: center;
        justify-content: center;
        /* margin: 0; */
    }
    #landing > h1 {
      margin-bottom: 15vh;
      color: white;
      font-family: Limelight;
      font-size: 300%
    }
</style>
