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
                <ion-item>Kam</ion-item>
                <ion-item>Tong</ion-item>
                <ion-item>Tam</ion-item>
                <ion-item>Wasawat</ion-item>
                <ion-item>Max</ion-item>
                <ion-item>Aaron</ion-item>
                            
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