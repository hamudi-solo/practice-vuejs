<template>
<h1>
    this is HomePage
</h1>
<p :class="CustomClass"> {{ content }}
</p>

<slot></slot>

</template>
<script>
export default {
     name: 'applyPage',
props:{
    CustomClass :{
        type: String,
        default: ''

    },
    content:{
        type: String,
        default:''
    }
}
}
</script>