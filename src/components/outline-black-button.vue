<template>
  <div class="outline-black-button-container" v-bind:class="rootClassName">
    <button class="outline-black-button-button button buttonSmall">
      {{ button }}
    </button>
  </div>
</template>

<script>
export default {
  name: 'OutlineBlackButton',
  props: {
    button: {
      type: String,
      default: 'Button',
    },
    rootClassName: String,
  },
}
</script>

<style scoped>
.outline-black-button-container {
  display: flex;
  position: relative;
}
.outline-black-button-button {
  color: var(--dl-color-secondary-700);
  cursor: pointer;
  outline: none;
  min-width: 150px;
  transition: 0.3s;
  padding-top: var(--dl-space-space-triplequarterunit);
  padding-left: var(--dl-space-space-fourunits);
  border-radius: var(--dl-radius-radius-radius75);
  padding-right: var(--dl-space-space-fourunits);
  padding-bottom: var(--dl-space-space-triplequarterunit);
}
.outline-black-button-button:hover {
  transform: scale(1.02);
}

@media(max-width: 1200px) {
  .outline-black-button-root-class-name {
    top: -25px;
    right: -540px;
    position: absolute;
  }
}
</style>
