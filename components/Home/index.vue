<template>
  <div>
    <button class="test"><NuxtLink to="/jodit">Jodit</NuxtLink></button>
    <button class="test"><NuxtLink to="/quil">Quil</NuxtLink></button>
    <button class="test"><NuxtLink to="/tiny">Tiny</NuxtLink></button>
    <button class="test">
      <NuxtLink to="/summer-note">JodSummerNoteit</NuxtLink>
    </button>
    <button class="test"><NuxtLink to="/nic-edit">NicEdit</NuxtLink></button>
    <button class="test"><NuxtLink to="/trix">Trix</NuxtLink></button>
  </div>
</template>

<script>
export default {};
</script>

<style>
.test {
  color: white;
  padding: 10px 30px;
  background: black;
}
a {
  color: white;
}
</style>