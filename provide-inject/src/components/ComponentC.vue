<template>
    <h1> Component C </h1>
    <h3> name  : {{Uname}}</h3>
</template>

<script>
export default {
    name : "ComponentC",
    inject :["Uname"]
}
</script>