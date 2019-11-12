<template>
    <div class="header">
        <p>
            This is a header!
        </p>
    </div>
</template>

<script>
export default {
    Name: "Header"
}
</script>

<style scoped>

.header{
    margin: 0;
    padding: 0;
    display: flex;
    width:100%;
    height: 50px;
    background-color: orange;
}
p{
    width: 100%;
    height: 100%;
    align-self: auto;
    text-align: center;
    color: whitesmoke;
}
</style>
