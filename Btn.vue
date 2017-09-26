<template>
      <v-btn fixed fab bottom right
        class="red" dark
        @click="click"
        >
        <slot />{{atom}}
      </v-btn>
</template>

<script>
export default {
  props: ['click'],
}

</script>
