<template>
<h1 :class="custom2class ">{{ content }}</h1>
<p>
    
</p>

</template>
<slot></slot>
<script>
export default{
    props:{
        custom2class:{
            type:String,
            default:''
        },
        content:{
            type:String,
            default:''
        },

    }
}
</script>