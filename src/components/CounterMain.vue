<template>
    <main class="counter__main">
        <button class="counter__name">
            <input type="text" value="Unnamed Counter">
            <i class='bx bx-edit'></i>
            <i class='bx bx-check-double'></i>
        </button>
        <div class="counter__count">3</div>
        <div class="counter__bottom">
            <div class="counter__left">
                <button class="counter__minus">
                    <i class='bx bx-minus-circle'></i>
                </button>
            </div>
            <div class="counter__right">
                <button class="counter__plus">
                    <i class='bx bx-plus-circle' ></i>
                </button>
            </div>
        </div>
    </main>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>