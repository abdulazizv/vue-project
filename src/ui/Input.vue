<template>
    <label :for="labelId" class="w-[300px] block my-3">
        <p class="text-indigo-500 my-2" v-if="placeholder">{{ placeholder }}</p>
        <input type="text" :id="labelId" class="p-3 w-full ring-2 focus:ring-cyan-700 focus:outline-none placeholder:text-slate-700" :placeholder="placeholder">
    </label>
</template>
<script>
export default {
    name:'Button',
    props: {
        labelId: String,
        placeholder: String,
        inputType : String
    }
}
</script>
<style lang="scss">
    
</style>