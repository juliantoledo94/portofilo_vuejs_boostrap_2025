<script setup>
import LeftCol from '../components/sections/aboutMe/LeftCol.vue';
import RightCol from '../components/sections/aboutMe/RightCol.vue';

</script>

<template>
    <section class="mt-5 mb-5 container">
        <h2 class="text-center fs-1">About me</h2>
        <div class="row d-flex  gap-3 mt-5 ">
            <div class="col-12 col-xl borders surface rounded-4">
                <LeftCol />
            </div>
            <div class="col-12 col-xl ">
                <RightCol />
            </div>
        </div>

    </section>
</template>


<style scoped>

</style>