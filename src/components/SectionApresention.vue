<template>
  <section class="section" id="about">
    <MyDescription></MyDescription>
      <div class="has-same-height is-gapless" style="display: flex; align-items: center; justify-content: center">
        <MyPerfil></MyPerfil>
        <MyImagemFullStack></MyImagemFullStack>
        <MyStacks></MyStacks>
      </div>
  </section>
</template>

<script lang="ts">
import {defineComponent} from 'vue';
import MyDescription from "@/components/SectionApresentetion/MyDescription.vue";
import MyPerfil from "@/components/SectionApresentetion/MyPerfil.vue";
import MyImagemFullStack from "@/components/SectionApresentetion/MyImagemFullStack.vue";
import MyStacks from "@/components/SectionApresentetion/MyStacks.vue";

export default defineComponent({
  name: 'SectionApresention',
  components: {MyStacks, MyImagemFullStack, MyPerfil, MyDescription}
});
</script>


<style scoped>

</style>
