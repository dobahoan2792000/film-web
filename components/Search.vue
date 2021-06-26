<template>
   <div class="bg-white shadow px-4 py-3 flex w-2/5">
        <span class="w-auto flex justify-end items-center text-gray-500 p-2">
            <font-awesome-icon :icon="['far', 'search']" class="mr-1"/>
        </span>
        <input class="w-full rounded p-2 border-none outline-none" type="text" placeholder="Try 'Los Angeles'">
        <button class="bg-blue-400 hover:bg-blue-300 rounded text-white p-2 pl-4 pr-4">
                <p class="font-semibold text-xs">Search</p>
        </button>
    </div>

</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>

</style>