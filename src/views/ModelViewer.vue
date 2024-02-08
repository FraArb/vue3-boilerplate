<script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/3.3.0/model-viewer.min.js"></script>

<template>
    <div class="mdv">
        <h1>Test</h1>
        <model-viewer
            id="mv-demo"
            shadow-intensity="1"
            src="/../../assets/fiat500_modified_compressed.glb"
            alt="A 3D model of an astronaut"
            auto-rotate
            camera-controls
            poster="/../../assets/fiat500_modified_compressed.glb"
        ></model-viewer>
    </div>
</template>

<style lang="scss">
.mdv {
    @apply lg:min-h-screen lg:flex lg:items-center;

    h1 {
        @apply text-xl font-medium text-white;
    }
}
</style>
