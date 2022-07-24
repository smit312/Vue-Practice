<template>
    <h1> Component A </h1>
    <ComponentBVue />
</template>

<script>
import ComponentBVue from './ComponentB.vue'
export default {
    name : "ComponentA",
    components :{ComponentBVue}
}
</script>