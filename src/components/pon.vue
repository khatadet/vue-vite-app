<script>
export default {
  data: () => {
    return {
      mas: "20",
    };
  },
};
</script>

<template>
  <div>
    <h1>Khatadet</h1>
    
      <img
      class= center
        alt="pon"
        src="../assets/168733165_2936104476620065_6789039554079085077_n.jpg"
        width="500"
        height="600"
      />
    
    <h1>{{ mas }}</h1>
  </div>
</template>

<style scoped>
a {
  color: #42b983;
}
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 40%;
}
</style>
