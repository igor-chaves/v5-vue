<script setup>
  // este Comp é o componente PAI
  import Comp from "@/components/Comp.vue"
</script>

<template>
  <main>
    <table border>
      <tr>
        <!-- estes Comp são os componentes filhos -->
        <td><Comp msg="--HELLO--" /></td>
        <td><Comp msg="--IGOR--" /></td>
      </tr>
      <tr>
        <!-- estes Comp são os componentes filhos -->
        <td><Comp msg="--CHAVES--" /></td>
        <td><Comp msg="--DONEGÁ--" /></td>
      </tr>
    </table>
  </main>
</template>
