<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Login</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true" class="bg">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">
          </ion-title>
        </ion-toolbar>
      </ion-header>
    
      <ExploreContainer name="Tab 1 page" />
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
// import ExploreContainer from '@/components/ExploreContainer.vue';

export default  {
  name: 'Tab1',
    components: {
    //ExploreContainer,
    IonHeader,
    IonToolbar,
    IonContent,
    IonPage,
  },
}
</script>