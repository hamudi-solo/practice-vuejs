/* eslint-disable */
<template>
<HomePage/>
<formPage/>
<applyPage CustomClass="bg-red-400" content="Hello Man"/>
<formPage custom2class="bg-green-400" @buttonAlert="buttonClick" content="Click me"/>


</template>

<script>
import HomePage from './components/HomePage.vue';
import formPage from './components/formPage.vue';
import applyPage from './components/applyPage.vue';
import contactPage from './components/contactPage.vue';
import ContactPage from './components/contactPage.vue';
export default {
  components:{HomePage,
    formPage,
    applyPage,
    ContactPage,
  },
methods:{
buttonClick (){
  alert ('Yes we can')
},
}
}
</script>
