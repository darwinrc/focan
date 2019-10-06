<template>
  <div class="home">
    <section class="home__left">
      <img class="home__left--image" alt="Cat picture" src="cat.png" />
    </section>
    <section class="home__right">
      <img class="home__right--image" alt="Focan Logo" src="logo-home.png" />
    </section>
  </div>
</template>

<style scoped lang="scss">
.home {
  display: flex;

  &__left {
    width: 50%;
    height: 100vh;

    &--image {
      width: 100%;
      height: 100%;
    }
  }

  &__right {
    display: flex;
    flex-direction: column;
    width: 50%;
    height: 100vh;
    justify-content: flex-end;
    align-items: flex-end;

    &--image {
      width: 90%;
      height: auto;
      margin-bottom: 100px;
    }
  }
}
</style>
