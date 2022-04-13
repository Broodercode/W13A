<template>
    <div>
     <h1>BODY</h1> 
     <IntroComponent />
     <ContentComponent />
     <ClosingComponent />
    </div>
</template>

<script>
  import IntroComponent from '@/components/body-components/IntroComponent.vue'
  import ContentComponent from '@/components/body-components/ContentComponent.vue'
  import ClosingComponent from '@/components/body-components/ClosingComponent.vue'

    export default {
        name: "PageBody",
        components: {
            IntroComponent,
            ContentComponent,
            ClosingComponent
   
    
  }
    }
</script>

<style scoped>

</style>