<template>
    <div class="wrapper">
        This is the homepage.
        <h3 class="wrapper-inside">
            This is the subtitle
        </h3>
    </div>
</template>

<script>
  export default {
    name: 'home-page'
  }
</script>

<style lang="postcss" scoped>
    :root {
        --color-main: blue;
    }

    .wrapper {
        font-size: 3rem;

        &-inside {
            font-size: 11rem;
        }
    }
</style>
