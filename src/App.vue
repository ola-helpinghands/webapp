<template lang="pug">
  #app
    nav#nav
      router-link(to="/")
        sui-button(primary) Home
      router-link(to="/about")
        sui-button(primary) About
    router-view
</template>

<style lang="scss">
</style>
