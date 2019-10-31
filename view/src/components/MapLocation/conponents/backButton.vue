<template>
    <div class="back">
       <md-button type="primary" @click="backTotrip">返回上一级</md-button>
    </div>
</template>
<script>

export default {
  name: 'back-button',
  methods: {
    backTotrip: function () {
      console.log('go back')
      this.$router.push('/trip')
    }
  }
}
</script>
