<template>
    <div class="home-carrousel-container">
        <div class="home-carrousel-title-container">
            <h2>{{ title }}</h2>
            <a :href="href">Mostrar todos</a>
        </div>
        <Splide :options="{gap:20, perPage: 4, padding:{left: 80, right: 80}}" class="home-carrousel">    
            <SplideSlide class="home-carrouse-item-container">
                <a href="#">
                    <div class="home-carrousel-item-image-container">
                        <div class="home-carrousel-item-image" style="background-image: url('https://digitalhub.fifa.com/transform/75ed55e7-7808-4a20-bfcc-0a58612a3b4b/548_FIFA-FAST_U-17-Women-s-World-Cup-Dominican-Republic-2024-Brand-Launch-Alex-Registr-your-Interest-Thumbnail-3840x2160?&io=transform:fill,aspectratio:16x9,width:450&quality=75');"></div>  
                    </div>
                    <div class="home-carrousel-item-text">
                        Registra tu interés en las entradas para la Copa Mundial de Beach Soccer de la FIFA Seychelles 2025™.
                    </div>
                </a>
            </SplideSlide>
            <SplideSlide class="home-carrouse-item-container">
                <a href="#">
                    <div class="home-carrousel-item-image-container">
                        <div class="home-carrousel-item-image" style="background-image: url('https://digitalhub.fifa.com/transform/75ed55e7-7808-4a20-bfcc-0a58612a3b4b/548_FIFA-FAST_U-17-Women-s-World-Cup-Dominican-Republic-2024-Brand-Launch-Alex-Registr-your-Interest-Thumbnail-3840x2160?&io=transform:fill,aspectratio:16x9,width:450&quality=75');"></div>  
                    </div>
                    <div class="home-carrousel-item-text">
                        Registra tu interés en las entradas para la Copa Mundial de Beach Soccer de la FIFA Seychelles 2025™.
                    </div>
                </a>
            </SplideSlide>
            <SplideSlide class="home-carrouse-item-container">
                <a href="#">
                    <div class="home-carrousel-item-image-container">
                        <div class="home-carrousel-item-image" style="background-image: url('https://digitalhub.fifa.com/transform/75ed55e7-7808-4a20-bfcc-0a58612a3b4b/548_FIFA-FAST_U-17-Women-s-World-Cup-Dominican-Republic-2024-Brand-Launch-Alex-Registr-your-Interest-Thumbnail-3840x2160?&io=transform:fill,aspectratio:16x9,width:450&quality=75');"></div>  
                    </div>
                    <div class="home-carrousel-item-text">
                        Registra tu interés en las entradas para la Copa Mundial de Beach Soccer de la FIFA Seychelles 2025™.
                    </div>
                </a>
            </SplideSlide>
            <SplideSlide class="home-carrouse-item-container">
                <a href="#">
                    <div class="home-carrousel-item-image-container">
                        <div class="home-carrousel-item-image" style="background-image: url('https://digitalhub.fifa.com/transform/75ed55e7-7808-4a20-bfcc-0a58612a3b4b/548_FIFA-FAST_U-17-Women-s-World-Cup-Dominican-Republic-2024-Brand-Launch-Alex-Registr-your-Interest-Thumbnail-3840x2160?&io=transform:fill,aspectratio:16x9,width:450&quality=75');"></div>  
                    </div>
                    <div class="home-carrousel-item-text">
                        Registra tu interés en las entradas para la Copa Mundial de Beach Soccer de la FIFA Seychelles 2025™.
                    </div>
                </a>
            </SplideSlide>
            <SplideSlide class="home-carrouse-item-container">
                <a href="#">
                    <div class="home-carrousel-item-image-container">
                        <div class="home-carrousel-item-image" style="background-image: url('https://digitalhub.fifa.com/transform/75ed55e7-7808-4a20-bfcc-0a58612a3b4b/548_FIFA-FAST_U-17-Women-s-World-Cup-Dominican-Republic-2024-Brand-Launch-Alex-Registr-your-Interest-Thumbnail-3840x2160?&io=transform:fill,aspectratio:16x9,width:450&quality=75');"></div>  
                    </div>
                    <div class="home-carrousel-item-text">
                        Registra tu interés en las entradas para la Copa Mundial de Beach Soccer de la FIFA Seychelles 2025™.
                    </div>
                </a>
            </SplideSlide>
        </Splide>
    </div>  
</template>

<script setup>

    defineProps({
        title: String,
        href: String
    });

</script>
