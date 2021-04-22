<template>
    <div>
        {{aa}}
    </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    setup() {
        
    },
    data(){
        return {
            aa:"aa"
        }
    },
    mounted(){
        this.aaa()
    },
    methods:{
        aaa(){
            var aa: string = "在在"
            console.log(aa)
        }
    }
})
</script>
<style scoped>

</style>
