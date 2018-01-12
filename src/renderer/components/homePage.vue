<template>
    <div class="wrapper">
        This is the homepage.
        <h3 class="inside">
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
        background-color: var(--color-main);

        & .inside {
            font-size: 1rem;
        }
    }
</style>
