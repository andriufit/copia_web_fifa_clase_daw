<template>
    <div class="new-main-container">
        <div class="left-container":style="{ backgroundImage: 'url(' + bannerImg + ')'}">
            <div class="left-content">
                <h3>{{bannerTitle}}</h3>
                <p>
                    {{bannerText}}
                </p>
                <a class="btn" :href="bannerLink">SIGUE LA ACCIÓN</a>
            </div>
        </div>

        <div class="right-container">

        </div>
    </div>
</template>

<script setup>
    const props = defineProps({
        //Img noticia
        newTitle: String,
        newImg: String,
        newText: String,
        newSubtitle: String,
        newLink: String,
        //Img banner izquierda
        bannerImg: String,
        bannerTitle: String,
        bannerText: String,
        bannerLink: String
    })
    

</script>
