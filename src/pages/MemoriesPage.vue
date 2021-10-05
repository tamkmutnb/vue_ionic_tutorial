<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-title>All Memories</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content>
            <h2>These are my memories - list to be added</h2>
            <ion-list>
                <ion-item>How to be a guy?</ion-item>
                <ion-item>Let's see what we got</ion-item>
                <ion-item>Fly to Japan</ion-item>
                <ion-item>Hiking Guide</ion-item>
                <ion-item>Let's go to the beach</ion-item>
                <ion-item>See Sea Cretures</ion-item>
                            
            </ion-list>


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
    IonList,
    IonItem, 

} from '@ionic/vue';
export default{
    components: {
        IonPage,
        IonHeader,
        IonTitle,
        IonContent,
        IonToolbar,
        IonList,
        IonItem,
    }
}
</script>