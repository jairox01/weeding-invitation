<template>
    <div class="container">
        <div class="weeding-date">
            <h3>NUESTRA FECHA</h3>
            <div class="date-container">
                <div class="day-name">
                    Viernes
                </div>
                <div class="date">
                    <span>20</span>
                    <span>06</span>
                    <span>2025</span>
                </div>
            </div>
        </div>
        <div class="countdown">
            <figure>
                <img src="../assets/img/countdown-bg.png" alt="">
                <div class="counter">
                    <div class="days">
                        <span>{{ countdown.days }} </span>
                        <span class="name">Días</span>
                    </div>
                    <div class="hours">
                        <span>{{ countdown.hours }}:</span>
                        <span class="name">Horas</span>
                    </div>
                    <div class="minutes">
                        <span>{{ countdown.minutes }}:</span>
                        <span class="name">Minutos</span>
                    </div>
                    <div class="seconds">
                        <span>{{ countdown.seconds }}</span>
                        <span class="name">Segundos</span>
                    </div>
                </div>
            </figure>
        </div>
    </div>
</template>

<script>
export default {
    name: 'DateComponent',
    data() {
        return {
            weddingDate: new Date('2025-06-20T16:00:00'),
            countdown: {
                days: 0,
                hours: 0,
                minutes: 0,
                seconds: 0
            }
        };
    },
    mounted() {
        this.calculateCountdown();
        setInterval(this.calculateCountdown, 1000);
    },
    methods: {
        calculateCountdown() {
            const now = new Date();
            const timeDiff = this.weddingDate - now;

            this.countdown.days = Math.floor(timeDiff / (1000 * 60 * 60 * 24));
            this.countdown.hours = Math.floor((timeDiff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            this.countdown.minutes = Math.floor((timeDiff % (1000 * 60 * 60)) / (1000 * 60));
            this.countdown.seconds = Math.floor((timeDiff % (1000 * 60)) / 1000);
        }
    }
};
</script>