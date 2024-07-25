<template>
  <div>
    <header>
      <nav>
        <ul>
          <Nuxtlink to="/">Nuxt Dojo Merch</Nuxtlink>
        </ul>
      </nav>
    </header>
    <!-- output -->
    <div>
      <slot />
    </div>
    <footer>
      <div>
        <p>FOOTER</p>
      </div>
    </footer>
  </div>
</template>

<style lang="scss" scoped></style>
