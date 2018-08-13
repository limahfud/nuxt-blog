<template>
    <div>
        The ID that you're using is be {{ $route.params.id }}
    </div>
</template>

<script>
export default {
    validate(data) {
        console.log(isNaN(data))
        return !isNaN(data.params.id)
    }
}
</script>

