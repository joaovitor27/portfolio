<template>
  <NavBar></NavBar>
  <SectionHeader></SectionHeader>
  <SectionApresention></SectionApresention>
  <SectionSkillsTags></SectionSkillsTags>
  <SectionServices></SectionServices>
  <SectionPortfolio></SectionPortfolio>
<!--  <SectionFormContact></SectionFormContact>-->
  <SectionMyResume></SectionMyResume>
  <FooterBar></FooterBar>
</template>

<script lang="ts">
import {defineComponent} from 'vue';
import NavBar from "@/components/NavBar.vue";
import SectionHeader from "@/components/SectionHeader.vue";
import SectionApresention from "@/components/SectionApresention.vue";
import SectionSkillsTags from "@/components/SectionSkillsTags.vue";
import SectionServices from "@/components/SectionServices.vue";
import SectionMyResume from "@/components/SectionMyResume.vue";
import SectionPortfolio from "@/components/SectionPortfolio.vue";
// import SectionFormContact from "@/components/SectionFormContact.vue";
import FooterBar from "@/components/Footer.vue";

export default defineComponent({
  name: 'HomePage',
  components: {
    FooterBar,
    // SectionFormContact,
    SectionPortfolio,
    SectionMyResume,
    SectionServices,
    SectionSkillsTags,
    SectionApresention,
    SectionHeader,
    NavBar
  }
});
</script>

<style scoped>

</style>
