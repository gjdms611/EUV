<template>
  <div>
    <v-text-field
            label="텍스트입력"
            v-model="testtext"
          ></v-text-field>
          <p>{{testtext}}</p>
  </div>
</template>

<script>

export default {
  name: 'home',
  data() {
    return {
      testtext:"",
      
    }
  }
}
</script>
