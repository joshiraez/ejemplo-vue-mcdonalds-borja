<template>
  <div>
    <button @click="elegir_bebida('Cola')">Cola</button>
    <button @click="elegir_bebida('Limon')">Limon</button>
    <button @click="elegir_bebida('Naranja')">Naranja</button>
    <br />
    <button @click="atras()">Atras</button>
  </div>
</template>

<script>
export default {
  name: "MenuBebida",
  methods: {
    elegir_bebida: function (tipo) {
      this.$emit("nueva-bebida", tipo);
    },
    atras: function (tipo) {
      this.$emit("atras");
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
