<template>
    <main class="counter container">
        <div class="counter__top">
            <div class="counter__grid">
                <button class="grid__list">
                    <i class='bx bxs-square-rounded' ></i>
                </button>
                <button class="grid__grid">
                    <i class='bx bxs-grid-alt'></i>
                </button>
            </div>
            <div class="counter__items">
                <button class="counter__btn">
                    <span>Counters</span>
                    <i class='bx bxs-down-arrow' ></i>
                </button>
                <div class="items__list">
                    <ul class="list__ul">
                        <li class="list__li">
                            <a href="#" class="list__time">
                                <span>Unnamed counter</span>
                                <i class='bx bx-check'></i>
                            </a>
                        </li>
                        <li class="list__li">
                            <a class="list__new" href="#">
                                <span>Add new counter</span>
                                <i class='bx bx-plus'></i>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="counter__setting">
                <button class="setting">
                    <i class='bx bxs-cog' ></i>
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