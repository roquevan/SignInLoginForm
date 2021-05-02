<template>
  <ion-page class="bg">
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>Text </ion-toolbar>
      </ion-header>
      <!-- <ExploreContainer name="Tab 1 page" /> -->
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonContent } from "@ionic/vue";
// import ExploreContainer from "@/components/ExploreContainer.vue";

export default {
  name: "Tab1",
  components: {
    //ExploreContainer,
    IonHeader,
    IonToolbar,
    IonContent,
    IonPage,
  },
};
</script>