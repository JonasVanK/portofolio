<template>
    <div class="hamburger">
        <span></span>
        <span></span>
        <span></span>
      </div>
</template>
<style scoped>
    .hamburger{
        display: flex;
        gap: .4rem;
        flex-direction: column;
    }
    span{
        display: block;
        width: 1.5rem;
        height: .1rem;
        background-color: blue;
    }
</style>