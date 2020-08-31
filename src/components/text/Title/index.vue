<template>
  <div class="title">
    <h1 class="title__mainTitle">{{ title }}</h1>
    <h5 class="title__subtext">{{ subText }}</h5>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    subText: {
      type: String,
      required: false,
    },
  },
}
</script>

<style lang="scss" scoped>
.title {
  &__mainTitle {
    color: $white;
  }

  &__subtext {
    color: $light-grey;
  }
}
</style>
