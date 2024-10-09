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
            
            <Splide id="News-splide" :options="{ rewinde: false, width: '100%', height: 'calc(90vh - 94px)' }" aria-label="My Favorite Images">
                <SplideSlide>
                
                    <div class="splide-item-container" style="background-image: url('https://digitalhub.fifa.com/transform/4e4717fc-7f87-4ea4-b989-7f5730ec94ae/General-Graphic-3840-x-2160-8?&io=transform:fill,aspectratio:16x9&quality=75');">
                        <div class="splide-item-text">
                            <span class="subtitle">
                                DESCUBRE
                            </span>
                            <h5>
                                Planteles oficiales para la Copa Mundial Femenina Sub-17
                            </h5>
                            <p>
                                Ya se conocen las listas de los equipos que competirán en República Dominicana. Choe Il Son, figura en el Sub-20 de Colombia, será el gran nombre.
                            </p>
                        </div>
                    </div>
                </SplideSlide>
                <SplideSlide>
                
                    <div class="splide-item-container" style="background-image: url('https://digitalhub.fifa.com/transform/3fac02c0-4860-4d98-9e6c-f242f8904f4c/Korea-DPR-v-Japan-Final-FIFA-U-20-Women-s-World-Cup-Colombia-2024?focuspoint=0.47,0.24&io=transform:fill,aspectratio:16x9&quality=75');">
                        <div class="splide-item-text">
                            <span class="subtitle">
                                DESCUBRE
                            </span>
                            <h5>
                                Planteles oficiales para la Copa Mundial Femenina Sub-17
                            </h5>
                            <p>
                                Ya se conocen las listas de los equipos que competirán en República Dominicana. Choe Il Son, figura en el Sub-20 de Colombia, será el gran nombre.
                            </p>
                        </div>
                    </div>
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
