<template>
    <div class="location">
        <h3>INFORMACIÓN CEREMONIA & RECEPCIÓN</h3>
        <div class="location-container">
            <p>Lugar: <b>Hacienda Villa Sara</b></p>
            <p>Dirección: Calle 246 # 7 - 17</p>
        </div>
        <div class="links">
            <a href="https://maps.app.goo.gl/JG17Va5RGWCiMcQT6" target="_blank" rel="noopener noreferrer">
                <img src="../assets/img/icons/maps.png" alt="">
                <span>Ver ruta en Google maps</span>
            </a>
            <a href="https://www.waze.com/live-map/directions/hacienda-villa-sara-calle-246-bogota?to=place.w.187433008.1874133475.17057975&from=ll.4.71218912%2C-74.06350621&utm_medium=lm_share_directions&utm_campaign=default&utm_source=waze_website" target="_blank" rel="noopener noreferrer">
                <img src="../assets/img/icons/waze.png" alt="">
                <span>Ver ruta en Waze</span>
            </a>
        </div>
        <div class="decoration">
            <picture>
                <img src="../assets/img/icons/flower-left.png" alt="">
            </picture>
        </div>
    </div>
</template>

<script>
export default {
    name: 'LocationComponent'
};
</script>