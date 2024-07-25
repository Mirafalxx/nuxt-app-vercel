<template>
  <div>
    <header>
      <nav>
        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products/13">Product-13</NuxtLink></li>
        </ul>
      </nav>
    </header>
    <!-- output -->
    <div>
      <slot />
    </div>
  </div>
</template>

<style lang="scss" scoped>
header {
  width: 100%;
  border-bottom: 1px solid #c3c3c3;
  padding: 10px 15px;
  nav {
    width: 100%;
  }
  ul {
    display: flex;
    gap: 15px;
    list-style-type: none;
    li {
      padding: 5px 7px;
      border-radius: 8px;
      border: 1px solid aquamarine;
      min-width: 125px;
      text-align: center;
      text-transform: uppercase;
      background-color: #e97070;

      font-weight: bold;
      a {
        text-decoration: none;
        &:visited {
          color: inherit;
        }
      }
    }
  }
}
.router-link-exact-active {
  color: #12b488 !important;
}
</style>
