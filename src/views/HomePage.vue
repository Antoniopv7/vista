<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Control de asistencia</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Blank</ion-title>
        </ion-toolbar>
      </ion-header>

      <div id="container">
        <!-- <strong>Ready to create an app?</strong>
        <p>Start with Ionic <a target="_blank" rel="noopener noreferrer" href="https://ionicframework.com/docs/components">UI Components</a></p>
        <ion-button expand="block">asd</ion-button> -->

        <ion-grid>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="6">
            </ion-col>
            <ion-col size="6">
            </ion-col>
          </ion-row>
          <ion-row size="12">
            <ion-col size="2"> </ion-col>
            <ion-col size="2">
              <ion-fab>
                <ion-fab-button color="dark">
                  <ion-icon :icon="scanCircle"></ion-icon>
                </ion-fab-button>
              </ion-fab>
            </ion-col>
            <ion-col size="4">
              <ion-button expand="block" color="dark">Asistencia</ion-button>
            </ion-col>
            <ion-col size="4"> </ion-col>
          </ion-row>
          <ion-row>
            <ion-col> </ion-col>
          </ion-row>
        </ion-grid>
      </div>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonCol,
  IonContent,
  IonFab,
  IonFabButton,
  IonGrid,
  IonHeader,
  IonIcon,
  IonPage,
  IonRow,
  IonTitle,
  IonToolbar,
} from "@ionic/vue";
import { IonButton } from "@ionic/vue";
import { defineComponent } from "vue";
import { scanCircle } from "ionicons/icons";

export default defineComponent({
  name: "HomePage",
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonTitle,
    IonToolbar,
    IonButton,
    IonGrid,
    IonCol,
    IonRow,
    IonFab,
    IonFabButton,
    IonIcon,
  },
  setup() {
    return { scanCircle };
  },
});
</script>

<style scoped>
.id {
  background-color: black;
}
.id2 {
  background-color: aqua;
}
</style>
