<template>
  <div class="heading">
    <h1>{{MainHeading}}</h1>
    <p>{{someText}}</p>
  </div>
</template>

<script>
export default {
    name:"TaskHeading",
    props:{
        MainHeading:{
            type: String,
            default: 'Some bullshit'
        },
        someText:{
            type: String,
            default: 'Create your own tasks'
        }
    }

}
</script>

<style>

    .heading{
        display: flex;
        align-items: center;
        font-size: x-large;
        flex-direction: column;
    }

</style>