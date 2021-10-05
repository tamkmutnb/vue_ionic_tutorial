<template>
    <base-layout page-title="All Memories">
            <ion-list>
                <ion-item>How to be a guy?</ion-item>
                <ion-item>Let's see what we got</ion-item>
                <ion-item>Fly to Japan</ion-item>
                <ion-item>Hiking Guide</ion-item>
                <ion-item>Let's go to the beach</ion-item>
                <ion-item>See Sea Cretures</ion-item>
            </ion-list>
    </base-layout>
</template>

<script>
import { 
    IonList,
    IonItem, 

} from '@ionic/vue';
export default{
    components: {
        IonList,
        IonItem,
    }
}
</script>