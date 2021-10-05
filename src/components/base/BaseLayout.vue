<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-title>{{pageTitle}}</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content>
            <h2>These are my memories - list to be added</h2>
            <slot />
        </ion-content>

    </ion-page>
</template>

<script>
import { 
    IonPage,
    IonHeader, 
    IonToolbar, 
    IonTitle, 
    IonContent,
} from "@ionic/vue";
export default{
    props: ['pageTitle'],
    components: {
    IonPage,
    IonHeader, 
    IonToolbar, 
    IonTitle, 
    IonContent,
    }
}
</script>