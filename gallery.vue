<template>
    <div class="gallery">
        <div class="gallery-panel" v-for="photo in photos" :key="photo.id">
            <img :src="photo.url">
        </div>
    </div>
</template>