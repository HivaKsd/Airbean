<template>
  <div class="landing">
    <img class="Logo2" src="../assets/logo.png" @click="ChangePage()"/>
  </div>
</template>

<script>
export default {
    methods : {
        ChangePage: function() {
            this.$root.$router.push("/Meny")
        }
    } 
    
}

</script>

<style scoped>
.landing {
    background-color: #0e927d;
    background-image: url("../assets/leaf22.png"), url("../assets/leaf1.png");
    background-repeat: no-repeat;
    background-position: left top, right top;
    background-size: auto 100%, auto 100%;
    height: 1080px;
    width: 100%;
    margin: 0%;
    padding: 0%;
    display: flex;
    justify-content: space-evenly;
    min-height: var(--minheight);
}
.Logo2 {
justify-self: center;
align-self: center;
cursor:pointer;
}
</style>