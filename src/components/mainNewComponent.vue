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
            
            <Splide :options="{ rewind: true }" aria-label="My Favorite Images">
                <SplideSlide>
                <img src="/img/ios.png" alt="Sample 1">
                </SplideSlide>
                <SplideSlide>
                <img src="/img/play.png" alt="Sample 1">
                </SplideSlide>
            </Splide>
          
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
