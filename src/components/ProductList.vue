<template>

    <ul class="catalog__list">
         <ProductListItem v-for="(item, index) in products" :product=item :key="index"/>
    </ul>
                
</template>

<script>
import ProductListItem from './ProductListItem.vue'


export default {
    components: {ProductListItem},
    props: ['products'],
}
</script>


