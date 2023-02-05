<template>
</template>
<script setup lang="ts">
import axios from 'axios';
axios
    .post('https://api.nhk.or.jp/v2/pg/genre/400/g1/0100/2023-02-12.json?key=npMMRYTXmAkwXKmQctzwDkPFFwsooICW', {
    }, {
        headers: {
            'Content-Type': 'multipart/form-data'
        }
    })
    .then(function(res){
        console.log(res.data)
    })
</script>

<style scoped>
</style>
  