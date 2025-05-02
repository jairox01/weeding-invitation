<template>
    <div class="itinerary">
        <div class="decoration">
            <picture>
                <img src="../assets/img/icons/decoration-right.png" alt="">
            </picture>
        </div>
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
                    <h4>3:45 pm.</h4>
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
        <div class="decoration last">
            <picture>
                <img src="../assets/img/icons/decoration-left-2.png" alt="">
            </picture>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ItineraryComponent'
};
</script>