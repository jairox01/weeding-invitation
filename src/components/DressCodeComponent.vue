<template>
    <div class="dress-code">
        <div class="container">
            <h3>ITINERARIO</h3>
            <div class="dress-columns">
                <div class="dress--column">
                    <picture>
                        <img src="../assets/img/icons/dress-man.png" />
                    </picture>
                    <h4>Hombre</h4>
                    <p>Smoking negro con corbatín (sin chaleco)</p>
                </div>
                <div class="dress--column">
                    <picture>
                        <img src="../assets/img/icons/dress-woman.png" />
                    </picture>
                    <h4>Mujer</h4>
                    <p>Vestido largo (Unicolor)</p>
                </div>
            </div>
        </div>
        <div class="container">
            <h4>Colores reservados</h4>
            <div class="color-columns">
                <div class="decoration">
                    <picture>
                        <img src="../assets/img/icons/flower-right.png" alt="">
                    </picture>
                </div>
                <div class="color--column">
                    <div class="bg-white circle"></div>
                    <h5>Blanco</h5>
                </div>
                <div class="color--column">
                    <div class="bg-beige circle"></div>
                    <h5>Hueso/Beige</h5>
                </div>
                <div class="color--column">
                    <div class="bg-green circle"></div>
                    <h5>Verde</h5>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'DressCodeComponent'
};
</script>