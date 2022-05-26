<template>
    <div class="container-fluid">
        <PostList/>
    </div>
</template>

<script>
import PostList from '../components/PostList.vue';
export default {
    nome: "App",
    
    components: { 
        PostList,
    }
}
</script>

<style lang="sass" scoped>

</style>