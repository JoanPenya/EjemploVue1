<template>
  <div class="titan">
    <p>Hay ángeles con rostro de satán</p>
    <p>Niños buscan las monedas por las que luchar</p>
    <p>Hay ángeles con rostro de satán</p>
    <p>Todos buscan su última oportunidad</p>
  </div>
</template>

<script>
export default {
  name: "Titan",
  props: {
    msg: String,
  },
};
</script>

<style>
.titan {
  position: absolute;
  width: 100%;
  text-align: center;
  color: red;
  bottom: 50%;
}
</style>