<template>
    <div class="itinerary">
        <h3>ITINERARIO</h3>
        <div class="itinerary-container">
            <div class="itinerary-item">
                <div class="item text-right">
                    <h4>3:00 pm.</h4>
                    <p>Recepción de invitados</p>
                </div>
                <div class="separator"></div>
                <div class="icon-item">
                    <img src="../assets/img/icons/hands.png" alt="">
                </div>
            </div>

            <div class="itinerary-item">
                <div class="icon-item text-right">
                    <img src="../assets/img/icons/coffee.png" alt="">
                </div>
                <div class="separator"></div>
                <div class="item text-left">
                    <h4>3:30 pm.</h4>
                    <p>Coffee station</p>
                </div>
            </div>
            <div class="itinerary-item">
                <div class="item text-right">
                    <h4>4:00 pm.</h4>
                    <p>Inicio de ceremonia</p>
                </div>
                <div class="separator"></div>
                <div class="icon-item">
                    <img src="../assets/img/icons/rings.png" alt="">
                </div>
            </div>
            <div class="itinerary-item text-right">
                <div class="icon-item">
                    <img src="../assets/img/icons/cups.png" alt="">
                </div>
                <div class="separator"></div>
                <div class="item text-left">
                    <h4>5:30 pm.</h4>
                    <p>Inicio de recepción</p>
                </div>
            </div>
        </div>
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
        </div>
    </div>
</template>

<script>
export default {
    name: 'ItineraryComponent'
};
</script>