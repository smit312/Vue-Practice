<template>
    <h1> Component B </h1>
    <ComponentCVue />
</template>

<script>
import ComponentCVue from './ComponentC.vue'
export default {
    name : "ComponentB",
    components :{ComponentCVue}
}
</script>