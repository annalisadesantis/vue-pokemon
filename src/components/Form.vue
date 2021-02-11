<template>
    <form @submit.prevent="search"
    class="form-inline d-flex justify-content-center mb-2">
        <input type="text" placeholder="cerca un pokemon"
        class="form-control">
        <input type="submit" value="Cerca" class="btn btn-primary ml-2">
    </form>
</template>

<script>
    export default {
        name: "Form"
    };
</script>
