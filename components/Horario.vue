<template>

<div>
    <b-form-select
      v-model="selected"
      :options="options"
      class="mb-3"
      value-field="item"
      text-field="name"
      disabled-field="notEnabled"
    ></b-form-select>

    <div class="mt-3">Selected: <strong>{{ selected }}</strong></div>
  </div>

</template>

<script>
  export default {
    data() {
      return {
        selected: 'A',
        options: [
          { item: 'Pilates, Yoga, Ballet e Programas de Emagrecimento', name: 'Option A' },
          { item: 'Musculação Feminina e Masculina', name: 'Option B' },
          { item: 'Dynamic Combat, Crossfit e Boxe ', name: 'Option C'},
          { item: 'Ritmos, Zumba Fitness e Jump', name: 'Option D' }


        ]
      }
    }
  }
</script>
