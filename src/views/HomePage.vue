<template>
  <ion-menu content-id="main-content">
    <ion-header class="ion-padding">
      <ion-toolbar>
        <ion-title>dev - Meet Up</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">This is the menu content.</ion-content>
  </ion-menu>
  <ion-page id="main-content" v-bind="$attrs">
    <ion-header class="ion-padding">
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-menu-button></ion-menu-button>
        </ion-buttons>
        <ion-title>dev - Meet Up</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">
      Tap the button in the toolbar to open the menu.
      <ion-button router-link="/profile">Default</ion-button>
    </ion-content>
  </ion-page>
</template>

<script>
import {
  IonButtons,
  IonContent,
  IonHeader,
  IonMenu,
  IonMenuButton,
  IonPage,
  IonTitle,
  IonToolbar,
  IonButton
} from '@ionic/vue';

export default {
  components: {
    IonButtons,
    IonContent,
    IonHeader,
    IonMenu,
    IonMenuButton,
    IonPage,
    IonTitle,
    IonToolbar,
    IonButton
  },
};
</script>
