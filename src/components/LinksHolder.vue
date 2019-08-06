<template>
    <div>
        <h5>Addtional links</h5>
        <div class="link-container">
        </div>
    </div>
</template>

<script>
    export default {
        name: "LinksHolder",
        data(){
            return{
                links: [{url: '/sport',name : 'Sport News ',},{url: '/economy',name: 'Economy News '},{url: '/latest',name : 'Latest News '}],
            }
        }
    }
</script>
