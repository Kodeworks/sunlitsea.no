<template>
  <section>
    <div>
      <h2>Prototype 2</h2>
      <p>
        Sunlit Sea recently deployed prototype 2 of our floating solar
        solution in the freezing water of the Oslo Fjord. Even at this stage,
        it's easy to see that our end game logistics solution seems within
        reach
      </p>
    </div>
    <iframe
        src="https://www.youtube-nocookie.com/embed/tiyVhSERi-g?modestbranding=1"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
    />
  </section>
</template>

<script>
export default {
  name: "PrototypeVideo"
}
</script>

<style scoped lang="scss">
section {
  @apply px-8 py-12 space-y-8 md:h-screen lg:px-24 lg:pt-0 lg:pb-0 lg:grid lg:grid-cols-2 lg:gap-32 lg:space-y-0 text-white;

  background: radial-gradient(circle at 25% center, lighten(black, 15%) 0%, black 50%);

  div {
    @apply space-y-4 md:space-y-8 lg:self-center;

    h2 {
      @apply text-4xl font-heading md:text-5xl;
    }

    p {
      @apply text-xl;
    }
  }

  iframe {
    @apply self-center w-full h-1/3 md:h-2/3;
  }
}
</style>