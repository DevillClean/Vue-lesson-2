<template>

    <Card :array-card="arrayCard" />

</template>


<script>
import { defineComponent } from 'vue';

import Card from '@/components/Card';



export default defineComponent({
  components: { Card },
    name: 'Cards',
    
    setup() {

        const arrayCard = [    
            { name: "user1", age: 12, src: 'https://placekitten.com/801/800', alt: "kitten_1" },
            { name: "user2", age: 15, src: 'https://placekitten.com/802/800', alt: "kitten_2" },
            { name: "user4", age: 11, src: 'https://placekitten.com/803/800', alt: "kitten_3" },
            { name: "user5", age: 19, src: 'https://placekitten.com/804/800', alt: "kitten_4" },
            { name: "user6", age: 25, src: 'https://placekitten.com/805/800', alt: "kitten_5" },
            { name: "user7", age: 36, src: 'https://placekitten.com/806/800', alt: "kitten_6" },
            { name: "user8", age: 90, src: 'https://placekitten.com/807/800', alt: "kitten_7" },
            { name: "user9", age: 57, src: 'https://placekitten.com/810/800', alt: "kitten_8" },
        ]

        return {
           arrayCard
        }
    }

})

</script>


<style>


</style>