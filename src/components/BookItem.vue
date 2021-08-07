<template>
    <li>{{book.title}}:{{book.author}}</li>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default {
    name:'BookItem',
    props:['book']
}

</script>

<style>
    li{
        display: block;
        margin: 0 10px;
    }
</style>
