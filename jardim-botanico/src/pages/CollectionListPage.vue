<template>
    <div class="q-pl-md q-pr-md">
        <h5>Acervo</h5>
        <CollectionList></CollectionList>
    </div>
</template>
  
<script>
import { defineComponent } from 'vue'
import CollectionList from 'src/components/CollectionList.vue'

export default defineComponent({
    name: 'CollectionListPage',
    components: {
        CollectionList
    },
})
</script>