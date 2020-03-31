<template>
    <div>
        
    <b-card v-for="(blog, key) in blogs" :key=key
        :title="blog.name"
        :img-src=getRandImage()
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="post mb-2"
    >
        <b-card-text>
        {{ blog.content }}
        </b-card-text>

        <b-button href="#" variant="primary">{{blog.author}}</b-button>
        
    </b-card>

    </div>
</template>

<script>
export default {
    name: 'BlogPost',
    props: ['blogs'],
    methods: {
        getRandImage() {
            return "https://picsum.photos/300/300?" + Math.random()
        }
    }

}
</script>

<style>
.post{
    padding: 10px;
    display: inline-flex !important;
    margin: 10px;
    
}
.card-img, .card-img-top {
    border-top-right-radius: calc(21.25rem - 1px) !important;
    height: 300px;
}
</style>