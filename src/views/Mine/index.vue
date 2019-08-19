<template>
    <div id="main">
        <Header title="我的喵喵"/>
        <div id="content">
            <Login/>
        </div>    
        <Tabbar/>
    </div>
</template>

<script>
import Header from "../../components/Header";
import Tabbar from "../../components/TabBar";
import Login from "../../components/Login"

export default {
    name: "Mine",
    components: {
        Header,
        Tabbar,
        Login
    }             
}
</script>

<style scoped>
    
</style>