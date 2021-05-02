<template>
  <ion-page class="bg">
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>Text </ion-toolbar>
      </ion-header>
       </ion-content>
      <ion-row class="form">
          <IonItem >
            <IonInput value={text} placeholder="Email" ></IonInput>
          </IonItem>
          <IonItem>
            <IonInput value={text} placeholder="Password"></IonInput>
          </IonItem>
          <IonButton expand="block">Login</IonButton>
      <!-- <ExploreContainer name="Tab 1 page" /> -->
    </ion-row>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonContent, IonItem, IonInput, IonButton, IonRow } from "@ionic/vue";
// import ExploreContainer from "@/components/ExploreContainer.vue";

export default {
  name: "Tab1",
  components: {
    //ExploreContainer,
    IonHeader,
    IonToolbar,
    IonContent,
    IonPage,
    IonItem,
    IonInput,
    IonButton,
    IonRow
  },
};
</script>