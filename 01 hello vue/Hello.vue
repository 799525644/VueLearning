<!-- vbase快捷生成 -->
<template>
    <div>
        <!-- vfor快捷生成 -->
        <div v-for="item in items" :key="item.id">
            {{ item }}
        </div>
    </div>
</template>

<script>
    export default {
        // vdata快速生成
        data() {
            return {
                key: value
            }
        },
        // vmethod
        methods: {
            name() {
                
            }
        },
        // vcomputed
        computed: {
            name() {
                return this.data 
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>