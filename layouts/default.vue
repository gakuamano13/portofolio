<template>
  <div class="hover-effect">
    <Nuxt />
  </div>
</template>
<script>
export default {

}
</script>

<style>
.hover-effect {
    animation-name: fadein;
    animation-duration: 2s;
}
@keyframes fadein {
from {
    opacity: 0;
    transform: translateY(10px);
}
to {
    opacity: 1;
    transform: translateY(0);
}
}
</style>
