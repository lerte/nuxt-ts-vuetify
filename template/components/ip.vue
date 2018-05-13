<template>
  <v-card>
    Your public ip is: {{ip}}
  </v-card>
</template>

<script lang="ts">
import {
  Component,
  Prop,
  Vue
} from "nuxt-property-decorator"
@Component({})
export default class Card extends Vue {
  @Prop() ip
}
</script>