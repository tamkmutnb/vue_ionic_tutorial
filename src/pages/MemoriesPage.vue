<template>
    <base-layout page-title="All Memories">
            <ion-list>
                <ion-item router-link="/memories/1">How to be a guy?</ion-item>

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
    },
    date(){
        return {
            memories: [
                {   id: 'm1',
                    image: "https://upload.wikimedia.org/wikipedia/commons/thumb/2/2e/Atlas_Mountains_snow_cover.jpg/640px-Atlas_Mountains_snow_cover.jpg",
                    title: 'A trip into the mountains',
                    description: 'It was a really nice trip',

                },
                {   id: 'm2', 
                    title: "Surfing the sea side",
                    description: "Feeling the cool breeze",

                },
                {   id: 'm3', 
                    title: 'Good eating',
                    description: 'Really tasty!',

                }
            ]
        };
    }
};
</script>