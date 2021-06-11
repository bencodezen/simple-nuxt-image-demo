<template>
  <div class="container">
    <nuxt-img
      src="/img/space.jpg"
      alt="Space by Jeremy Thomas on Unsplash"
      sizes="xl:100vw lg:100vw md:100vw sm:100vw xs:100vw"
    />
    <p>
      Photo by
      <a
        href="https://unsplash.com/@jeremythomasphoto?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText"
      >
        Jeremy Thomas
      </a>
      on
      <a
        href="https://unsplash.com/s/photos/space?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText"
      >
        Unsplash
      </a>
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
