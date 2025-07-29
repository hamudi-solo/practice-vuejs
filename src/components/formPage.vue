<template>
    <div class="ml-4 flex justify-center items-center">
<button :class="CustomClass" @click="$emit('buttonAlert')">{{content}}/>
 </div>
</template>
<script>
export default {
props:{
    CustomClass:{
        type:String
    
    },
    content:{
        type: String
    },
}
}
</script>