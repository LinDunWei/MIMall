<template>
    <div>
        <h1>Order</h1>
        <order-header></order-header>
        <router-view></router-view>
        <nav-footer></nav-footer>
    </div>

</template>

<script>
import OrderHeader from '../../components/OrderHeader'
import NavFooter from '../../components/NavFooter'
export default {
    components:{
        OrderHeader,NavFooter
    }
}
</script>

<style scoped>

</style>