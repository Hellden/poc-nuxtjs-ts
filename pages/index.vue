<template>
  <section class="section">
    <div class="columns is-mobile">
      <card title="Free" icon="github-circle">
        Open source on
        <a href="https://github.com/buefy/buefy">
          GitHub
        </a>
      </card>

      <card title="Responsive" icon="cellphone-link">
        <b class="has-text-grey">
          Every
        </b>
        component is responsive
      </card>

      <card title="Modern" icon="alert-decagram">
        Built with
        <a href="https://vuejs.org/">
          Vue.js
        </a>
        and
        <a href="http://bulma.io/">
          Bulma
        </a>
      </card>

      <card title="Lightweight" icon="arrange-bring-to-front">
        No other internal dependency
      </card>
    </div>

    <h1>Test de rapidité</h1>
  </section>
</template>

<script lang="ts">
import Card from '../components/Card.vue'

export default {
  components: {
    Card,
  },
  methods: {
    handleTest() {
      const test: string = 'coucou'
      console.log(test)
    },
  },
  head() {
    return {
      title: 'Accueil',
    }
  },
}
</script>
