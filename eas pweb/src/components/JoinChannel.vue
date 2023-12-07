<template>
  <div>
    <input type="text" v-model="channelCode" placeholder="Enter channel code" />
    <button @click="joinChannel">Join Channel</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      channelCode: '',
    };
  },
  methods: {
    joinChannel() {
      // Implement logic to join a channel
      // This might involve sending an API request to your backend
    },
  },
};
</script>
