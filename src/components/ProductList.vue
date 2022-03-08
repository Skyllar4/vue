<template>

    <ul class="catalog__list">
         <ProductListItem v-for="(item, index) in products" :product=item :key="index"/>
    </ul>
                
</template>

<script>
import ProductListItem from './ProductListItem.vue'
import products from '../data/products'


export default {
    components: {ProductListItem},
    computed: {
        products() {
            return products
        }
    }
}
</script>


