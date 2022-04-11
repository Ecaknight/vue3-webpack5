<template>
    <div>
        <div>解析Vue文件了哟~</div>
        <p>{{name}}</p>
        <div>臣妾做不到</div>
    </div>
</template>
<script lang="js">
import { defineComponent, ref } from 'vue';
export default defineComponent({
    setup() {
        const name = ref('txm')

        return {
            name
        }
    }
})
</script>