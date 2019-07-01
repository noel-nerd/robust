<template>
  <q-page class="">
    <div class="row">

      <q-input class="col-6 q-pa-sm"
        v-model="text"
        filled
        type="textarea"
      />
      <q-input class="col-6 q-pa-sm"
        v-model="text"
        filled
        type="textarea"
      />
    </div>

  </q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'PageIndex',
  data () {
    return {
      text: 'oi'
    }
  },
  methods: {

  }
}
</script>
