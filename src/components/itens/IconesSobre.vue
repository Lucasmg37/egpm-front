<template>
    <div class="col-12 py-2">
        <div class="row mb-3">
            <div class="col-6 bloco-icon py-4">
                <div class="row">
                    <span class="col-12 icon-box-sobre text-center my-auto"><i class="fa fa-clock"></i></span>
                    <span class="col-12 text-box-sobre text-center">+ DE 37 HORAS</span>
                </div>
            </div>
            <div class="col-6 bloco-icon py-4">
                <div class="row">
                    <span class="col-12 icon-box-sobre text-center my-auto"><i class="fa fa-user"></i></span>
                    <span class="col-12 text-box-sobre text-center">+ DE 700 VISITANTES</span>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-6 bloco-icon py-4">
                <div class="row">
                    <span class="col-12 icon-box-sobre text-center my-auto"><i class="fa fa-gamepad"></i></span>
                    <span class="col-12 text-box-sobre text-center">+ DE 20 CAMPEONATOS</span>
                </div>
            </div>
            <div class="col-6 bloco-icon py-4">
                <div class="row">
                    <span class="col-12 icon-box-sobre text-center my-auto"><i class="fa fa-trophy"></i></span>
                    <span class="col-12 text-box-sobre text-center">+ DE 100 PREMIAÇÕES</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "BlocoIcons"
    }
</script>

<style scoped lang="scss">
    
    .icon-box-sobre {
        font-size: 2.5rem;
        @include sm {
            font-size: 3rem;
        }
    }

    .text-box-sobre {
        font-size: 1rem;
        @include sm {
            font-size: 1.2em;

        }
        font-weight: bold;
    }

</style>
