<template>

    <ul class="catalog__list">
         <ProductListItem v-for="item in ProductListItem" :key="item"/>
    </ul>
                
</template>

<script>
import ProductListItem from './ProductListItem.vue'

export default {
    components: {ProductListItem},
}
</script>


