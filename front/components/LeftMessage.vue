<template>
  <div class="left-message">
    <span class="left-message__name">{{ userName }}</span>
    <span>came out of the chat</span>
  </div>
</template>

<script>
export default {
  props: {
    userName: String,
  },
};
</script>

<style lang="scss" scoped>
.left-message {
  width: 90%;

  margin-top: 1em;
  padding: 0.6em;

  font-size: 15px;
  text-align: center;

  border-radius: 4px;

  box-shadow: inset 0px 0px 4px $color2;

  &__name {
    color: $color5;
  }
}
</style>
