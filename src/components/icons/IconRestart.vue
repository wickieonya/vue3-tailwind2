<template>
<svg :height="height" :width="width" viewBox="0 0 32 32" class="fill-current">
 <path d="M26,18A10,10,0,1,1,16,8h6.1821l-3.5844,3.5854L20,13l6-6L20,1,18.5977,2.414,22.1851,6H16A12,12,0,1,0,28,18Z"/></svg>
</template>
<script> 
export default
{ name:"IconRestart", 
 props:{ height: { type:  Number, default: 20, }, width: { type:  Number, default: 20, }, } 
}
</script>