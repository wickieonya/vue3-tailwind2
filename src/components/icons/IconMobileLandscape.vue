<template>
<svg :height="height" :width="width" viewBox="0 0 32 32" class="fill-current">
 <path d="M3,10V22a2.002,2.002,0,0,0,2,2H27a2.0023,2.0023,0,0,0,2-2V10a2.0027,2.0027,0,0,0-2-2H5A2.0023,2.0023,0,0,0,3,10Zm2,0,2,0V22H5ZM27,22H9V10H27Z"/></svg>
</template>
<script> 
export default
{ name:"IconMobileLandscape", 
 props:{ height: { type:  Number, default: 20, }, width: { type:  Number, default: 20, }, } 
}
</script>