<template>
  <div class="home">
    Event Hub Name: {{ eventHubName }}
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  data() {
    return {
      eventHubName: process.env.VUE_APP_EVENTHUB_NAME,
    };
  },
  components: {

  },
  methods: {

  },
};
</script>
