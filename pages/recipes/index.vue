<template>
    <section class="recipes">
        <Recipe
        thumbnail="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRVRGkcPMvFhzwutW5GpUE4VgqFOIZoqpYz-w&usqp=CAU"
        title="title"
        previewText="some nice preview"
        />
        <Recipe
        thumbnail="https://www.iamexpat.de/sites/default/files/styles/ogimage_thumb/public/german-food-cuisine-dishes.jpg?itok=aC12c0xI"
        title="title"
        previewText="some nice preview"
        />
        <Recipe
        thumbnail="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQRq-2h3mMpVqmS7Qcjctdkpiza6D573nocrw&usqp=CAU"
        title="title"
        previewText="some nice preview"
        />
    </section>
</template>
<script scoped>
import Recipe from '@/components/Recipe'
export default {
    components: {
        Recipe
    }
}
</script>
<style scoped>
.recipes{
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    align-items: center;
}


</style>